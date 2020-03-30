---
layout: post
title:  Your First Task in Rplexus.net
categories: [Beginner]
---

<iframe style="width:60vh; height:calc(60vh/1.77);" src="https://www.youtube.com/embed/Ozr7-fHbdy0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The codes in example;

```python
    def prepare(self):
        self.my_sw1 = self.taskAlias("sw1")
```

````python
    async def pre_update(self):
        if(random.randrange(10) > 5):   self.my_sw1.data = True
        else: self.my_sw1.data = False
````

````python
    async def post_update(self):
        if("sw1" in self.usertask):
            print(self.usertask["sw1"])
            self.my_sw1.data = self.usertask["sw1"]
````
