How to use
===

### Show

###### Success

```
Notification.Show("this is a success messsage", "success");
```

###### Error

```
Notification.Show("this is a error messsage", "error");
```

###### Disable auto hide
```
Notification.Show("this is a warning messsage", "warning", {autoHide: false});
```

###### Change auto hide time
```
Notification.Show("this is a success messsage", "success", {hideAfter: 1000}); //1000ms = 1sec
```

### Hide
```
Notification.Hide();
```

To Do
===
1. Add screenshots to README
2. Add animations along with options
3. Support for mobile
4. Host it on CDN
