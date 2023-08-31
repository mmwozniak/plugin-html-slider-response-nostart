# jsPsych slider response but without the starting position

The code is the jsPsych slider-response plugin but the response marker appears only after clicking on the slider. Lack of the marker's starting position allows to avoid anchoring effect caused by the initial position.
Link to the description of the original plugin: https://www.jspsych.org/7.0/plugins/html-slider-response/

Use it just like a normal jsPsych plugins, but remember to refer to the files in your HTML head:

```
 <script src="plugin-html-slider-response-nostart.js"></script>
 <link href="jspsych_extra.css" rel="stylesheet" type="text/css" />
```

Tested on jsPsych 7.1.2
