# How to install
Put RapidCode.xml file into following directories
* Windows: <your_user_home_directory>\.IntelliJ IDEA<version_number>\config\templates
* Linux: ~IntelliJ IDEA<version>/config/templates
* OS X: ~/Library/Preferences/IntelliJ IDEA<version>/templates

# RapidCode

#### Rsnack
Creates and shows simple snackbar:
```java
Snackbar.make(, "", Snackbar.LENGTH_LONG).show();
```
#### Rsnackwclick 
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
#### Toast
Creates simple toast message:
```java
Toast.makeText(, "", Toast.LENGTH_SHORT).show();
```

