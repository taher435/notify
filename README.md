How to use
===

###Show

######Success 

```
Notify.Show("this is a success messsage", "success");
```

######Error 

```
Notify.Show("this is a error messsage", "error");
```

######Disable auto hide
```
Notify.Show("this is a warning messsage", "warning", {autoHide: false});
```

######Change auto hide time
```
Notify.Show("this is a success messsage", "success", {hideAfter: 1000}); //1000ms = 1sec
```

###Hide
```
Notify.Hide();
```

To Do
===
1. Add screenshots to README
2. Add animations along with options
3. Support for mobile
4. Host it on CDN