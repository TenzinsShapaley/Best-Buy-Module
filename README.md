# Best-Buy-Module

1. 
https://chromedriver.storage.googleapis.com/index.html?path=89.0.4389.23/
Install the chromedriver that is needed for selenium

2. 
unzip it to where you want
E.G. : D:\Downloads\chromedriver_win32\chromedriver
In the gui browser path, provide the path to the chromedriver.
Use double slashes since its windows, for example:
```
D:\\Downloads\\chromedriver_win32\\chromedriver
```


3. 
for the item sku/link, only link is currently supported
so go ahead and use the 5800x for that for testing since everything else is OOS for queue items

4. 
item nickname doesn't matter (can even be blank)
so you can put anything there
Add Item is not currently supported, but will be in the futre
but after 3 of those fields are filled out, you can hit start queue

5. 
clicking the Auto Cart check box allows the program to auto add to cart and take you to the checkout link, but will not do the checkout itself 

6. 
Maax Queue Time will choose a max queue time that the software will accept. If a queue time is larger than the max queue time, the software will discard the queue and you will have to queue up again. If it is left blank at the start, it will default to 3600 seconds, (so realistically it will accept any queue time BB gives the user)
