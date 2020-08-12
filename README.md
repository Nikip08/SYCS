class dequeue()
      def__init__(self):
            self._data=[]
    def__len__(self):
        len(self._data)
    def__display():
        print(self._data)
    def is__empty(self):
        return len(self._data)==0
    def add__first(self,value):
        self._data.append(value)
    def add__last(self,value):
        self._data.insert(0,value)
    def del__first(self):
        return self._data.pop()
    def del__last(self):
        return self._data.pop(0)
    def first(self):
        if self.is__empty():
            raise exception
        return self.data[0]
