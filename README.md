<p align="center">
  <img width="350" height="350" src="https://raw.githubusercontent.com/sys113/tekrar/master/tekrar.png">
</p>

---
<div align="center">
  
![](https://img.shields.io/github/stars/SYS113/tekrar.svg)
![](https://img.shields.io/badge/language-python-orange.svg)
![](https://img.shields.io/github/forks/SYS113/tekrar.svg)
![](https://img.shields.io/github/release/SYS113/tekrar.svg)
![](https://img.shields.io/github/issues/SYS113/tekrar.svg)
![](https://img.shields.io/badge/license-MIT-informational.svg)
</div>

---
## *what is <ins>tekrar</ins>*
*create loading animation in python cli project ...<br />*

---
## *description*
  + #### *speed*
    ```python
      # set loading speed ...
      # range 1 to 10 ...
      
      speed = 5
    ```
    
  + #### *method*
    ```python
      # set loading method ...
      # only 1 or 2 ...
      
      method = 2
    ```
    
  + #### *sleep*
    ```python
      # Show loading for 8 second ...
      # can be of type int or float ...
      # cannot use simultaneously 'sleep' and 'function' argument ...
      
      sleep = 8
    ```
    
  + #### *function*
    ```python
      # Show loading if 'x' function running ...
      # cannot use simultaneously 'sleep' and 'function' argument ...
      
      function = x
    ```
    
   + #### *args*
   ```python
   # if function has arguments then use this way ...
   # type 'args' only list ...
   
   args = ['tekrar','SYS113']
