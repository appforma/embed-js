embed-js
========

The Appforma Javascript embed framework

To embed the Appforma promotion widget on your website, add the following to any page you would like the widget to appear on, just include the following HTML snippet:

```
<script type="text/javascript" src="https://s3.amazonaws.com/appforma_static/embed/maverick.js"></script>
<script type="text/javascript">
  if (typeof(Maverick) !== "undefined") {
    Maverick.init({
      acc_hash: "f1ec7ee7d2719555ba6d428fee62837a",
      placement: "right"
    });
  }
</script>
```

### Available options: ###
| Option | Description |
| ------ | ----------- |
| acc_hash   | Your Appforma account embed hash. You can find it in the publish channels page in Appforma. |
| placement | Where you want the widget to appear (left / center / right) |

