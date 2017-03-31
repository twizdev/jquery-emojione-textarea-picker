# jQuery EmojiOne Textarea Picker

This a lightweight ( 29.2 KB ) plugin that adds an emojiOne emoji picker to a textarea.
You can choose to send the shortcode ( eg: `:smiley:` ) or the unicode ( ☺ ) to the textarea.


###### Requires
* jQuery


## Usage

Include the plugin and css in the page header:
```
<link rel="stylesheet" href="file/to/path/css/emojione.picker.css">
<script type="text/javascript" src="file/to/path/js/emojione.picker.min.js"></script>
```

Simple Usage
```
<textarea id="txt1"></textarea>
<script type="text/javascript">
	$( "#txt1" ).emojionePicker();
</script>
```

###### Defaults
```
$( "#txt1" ).emojionePicker({
	pickerTop : 5,
	pickerRight : 5,
	type : "shortcode",
});
```

###### Options
* **pickerTop**   - Emoji picker top margin
* **pickerRight** - Emoji picker right margin
* **type**        - What to send to textarea, valid values are `shortcode` and `unicode`
