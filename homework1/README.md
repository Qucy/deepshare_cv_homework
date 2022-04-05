## Homework 1

Coding homework - finish a image classification model using Pytorch

Q1 - Explain ```__getitem__()``` function in Pytorch ```Dataset```
- ```__getitem__()``` method start and ends with 2 underscores, it's a special method in Python, usually call this type of method ```dunder method```

- when you implement ``__getitem__()`` for a collection class in Python, you will get the benefit when calling iteration, slicing or other build-in method,  it will automatically call the ``__getitem__()`` method implemented by you

- for this question, in the context of ```pytorch Dataset``` , you have to implement this method if you want to have your own customized dataset. Below is comment written in the ```Pytorch``` source code.

  ```python
      """
      All datasets that represent a map from keys to data samples should subclass
      it. All subclasses should overwrite :meth:`__getitem__`, supporting fetching a
      data sample for a given key. Subclasses could also optionally overwrite
      :meth:`__len__`, which is expected to return the size of the dataset by many
      :class:`~torch.utils.data.Sampler` implementations and the default options
      of :class:`~torch.utils.data.DataLoader`.
      """
  ```

Q2 - Explain debug function, Step Over\Step Into\Step Out\Run to Cursor
- Step over means jump over to the next line and will not enter the function,
- Step into means jump into a function,
- Step out means jump out a function
- Run to cursor mean jump to the cursor directly.

Q3 - Explain the ```logging```, ```argparse``` and ```sys.path``` module in Python
- ```logging``` provide by Python officially, for more read the doc here -> https://docs.python.org/3/library/logging.html
- ``` argparse ``` is parse for command line options, arguments and sub-commands -> https://docs.python.org/3/library/argparse.html
- ```sys.path``` is an attribute for sys module, contains a list of strings specifies the search path for modules. -> https://docs.python.org/3/library/sys.html?highlight=sys%20path#sys.path





 
