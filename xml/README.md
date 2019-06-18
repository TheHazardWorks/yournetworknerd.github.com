# Custom DTD Files



## Fursona Markup Language (.furml)
A markup language designed to store a fursona or even several at a time. The basic template is below:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE fursona SYSTEM "https://yournetworknerd.github.io/xml/fursona.dtd">
<fursona name="" species="" gender="">
  <creator>
    <name><!-- Your Name --></name>
    <email><!-- Your Email --></email> <!-- Optional -->
    <social-account><!-- Social Network Link --></social-account>
  </creator>
  <refsheet><!-- Refsheet Image Link --></refsheet>
  <created><!-- Timestamp of Creation --></created>
  <home><!-- Characters Home --></home> <!-- Optional -->
  <biography><!-- Characters Biography --></biography>
</fursona>
```
