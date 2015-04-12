# PDW Toggle Toolbars (TinyMCE)
A plugin for the TinyMCE WYSIWYG editor. The plugin shows and hides the toolbars just like the Kitchen Sink plugin in Wordpress.

##Installation

```javascript
 $('textarea#example1').tinymce({
    script_url : "javascript/tiny_mce/tiny_mce.js",

    // General options
    theme : "advanced",
    plugins : "pdw, safari,pagebreak,style,layer,table,save,advhr,advimage,advlink,emotions,iespell,inlinepopups,insertdatetime,preview,media,searchreplace,print,contextmenu,paste,directionality,fullscreen,noneditable,visualchars,nonbreaking,xhtmlxtras,template",
 
    // Theme options
    theme_advanced_buttons1 : "pdw_toggle, save,newdocument,|,bold,italic,underline,strikethrough,|,justifyleft,justifycenter,justifyright,justifyfull,styleselect,formatselect,fontselect,fontsizeselect",
    theme_advanced_buttons2 : "cut,copy,paste,pastetext,pasteword,|,search,replace,|,bullist,numlist,|,outdent,indent,blockquote,|,undo,redo,|,link,unlink,anchor,image,cleanup,help,code,|,forecolor,backcolor",
    theme_advanced_buttons3 : "tablecontrols,|,hr,removeformat,visualaid,|,sub,sup,|,charmap,emotions,iespell,media,advhr,|,print,|,ltr,rtl",
    theme_advanced_buttons4 : "insertlayer,moveforward,movebackward,absolute,|,styleprops,|,cite,abbr,acronym,del,ins,attribs,|,visualchars,nonbreaking,template,pagebreak",
    theme_advanced_toolbar_location : "top",
    theme_advanced_toolbar_align : "left",
        
    pdw_toggle_on : 1,
    pdw_toggle_toolbars : "2,3,4",
        
    height : '300',
    width : '450'
});
```

- Extract zip-file
- Copy pdw folder to the plugins folder under tiny_mce (/tiny_mce/plugins/)
- See above source code for how to add the plugin to your editor setup.