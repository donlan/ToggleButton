# ToggleButton
A custom view of ToggleButton with flat UI style


## See it:
![](/screenshot/demo_desc.png)

## how to use

**attrs**
```xml
<declare-styleable name="ToggleButton">
      <attr name="tb_uncheck_color" format="color"/>
      <attr name="tb_check_color" format="color" />
      <attr name="tb_check_bg_color" format="color" />
      <attr name="tb_uncheck_bg_color" format="color"/>
      <attr name="tb_circle_radius"  format="dimension"/>
      <attr name="tb_shadow_color" format="color"/>
      <attr name="tb_shadow_radius" format="dimension"/>
</declare-styleable>
```


**xml**

```xml
   <dong.lan.library.ToggleButton
      app:tb_circle_radius="15dp"
      app:tb_shadow_radius="2dp"
      app:tb_check_bg_color="#C264FE"
      app:tb_check_color="#7A08FA"
      android:layout_width="wrap_content"
      android:layout_height="wrap_content" />
```

### Tips:
tb_circle_radius is the most import attribute,because I use it to measure the view's width and height.

To get more detail,please go to see [ToggleButton.java](/library/src/main/java/dong/lan/library/ToggleButton.java)
