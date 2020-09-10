#Simply minimalistic skin for datepicker calendar.

##States

+ Normal

![Datepicker normal](images/screenshot.png)

+ Hover on day

![Datepicker hover](images/screenshot-hover.png)

+ Day selected

![Datepicker active](images/screenshot-active.png)

##Possibilities for customize

You have possibility to change text color, background color and highlight colors. For this go to `less` directory and change variables:

```less
@background: #FFFFFF;
@font: #303C47;
@highlight: #339D85;
```

After this run:

```bash
lessc less/datepicker-skin.less dist/datepicker-skin.css
```
