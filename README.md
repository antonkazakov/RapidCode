# RapidCode

##### Rsnack
Creates and shows simple snackbar:
```java
Snackbar.make(, "", Snackbar.LENGTH_LONG).show();
```
##### Rsnackwclick 
Creates and shows snackbar with OnClickLisntener:
```java
Snackbar snack = Snackbar.make(, "", Snackbar.LENGTH_INDEFINITE);
                snack.setAction("", new View.OnClickListener() {
                    @Override
                    public void onClick(View view) {
                        
                    }
                });
                snack.show();
```
##### Toast
Creates simple toast message:
```java
Toast.makeText(, "", Toast.LENGTH_SHORT).show();
```

