# internetshutdowns.in

## Description

    Working on issues with partnerd project "internetshutdowns.in"

### Issue #1

    Readme.md file has been changed

    changes made:
        - Changed github link to github link

```bash
- $ git clone https://gitlab.com/sflcin/internetshutdowns.in.git
```

### Issue #18

    Footer text spacing + font size + text background + color combination

    Changes made:
        - Changed font color from white to black
    File path:
        - internetshutdowns.in/static/css/footer.css

```bash
color: #00000;
```

### Issue #20

    Hyperlink issues in same tab

    changes made:
        - hyperlink in Resource:policy traks "reade more" links in another tab
    File path:
        - internetshutdowns.in/resources/templates/resource/policy-tracker.html

```bash
<a class="forth-container-col-3-txt-2" href="{{ post.url }}" target="_blank" id="read-more">Read more</a>
```

### Issue #23

    Inconsistent font size and style, text spacing, links opening in a same tab

    Changes made:
        - added font size for description and changed links opening in same tab
    File path:
        - internetshutdowns.in/resources/templates/resources/litigate.html
        - internetshutdowns.in/static/litigation/litigation.css

```bash
<a class="forth-container-col-3-txt-2" href="{{ post.url }}" target="_blank" id="read-more">Read more</a>

.forth-container-col-3-txt-2 {
  margin-top: 15px;
  color: rgb(39, 131, 207);
  font-weight: 600;
}
```

### Issue #13

    Spacing of a text

    Changes made:
        - changed spacing issues in "share your experience form"
    File path:
        - internetshutdowns.in/static/css/indexfile.css

```bash
.form-content{
  word-spacing: normal;
}
```
