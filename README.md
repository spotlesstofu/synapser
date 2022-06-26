# synapser



## Usage

Find the mappings xml:
1. open [razer synapse](https://www.razer.com/it-it/synapse-3)
1. export your profile
1. rename the file as .zip
1. extract the .zip
1. in the Features folder find the mappings xml file, it starts with something like this
```xml
<?xml version="1.0"?>
<Mappings 
```

Parse the mappings xml:
1. open `index.html` in browser
1. paste your xml in the text field
1. press parse
1. the `output` object will be populated, you can view it from the console (`Ctrl+Shift+I`)

## History

A [reddit thread](https://www.reddit.com/r/razer/comments/k4fps6/how_do_you_read_the_exported_synapse_3_macro_xml/) got me to start this.

# Links

[usb_hid_usages](http://www.freebsddiary.org/APC/usb_hid_usages.php).