

```python
class queue:
    def __init__(self):
        self.data=[]
        
    def enqueue(self, value):
        self.data.append(value)
        
    def dequeue(self):
        data=self.data[0]
        del self.data[0]
        return data
    
    def size(self):
        return len(self.data)
    
que=queue()

que.enqueue(10)
que.enqueue(15)
que.enqueue(23)
que.enqueue(52)
que.size()
que.dequeue()
que.size()
```




    3


