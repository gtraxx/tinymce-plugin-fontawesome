# tinymce-plugin-fontawesome
A plugin that lets you insert FontAwesome icons via TinyMCE.
![font-awesome-feature](https://cloud.githubusercontent.com/assets/356674/16452431/c8f2e12a-3e08-11e6-9327-dd1647f4ae3f.jpg)

### Preview
![fireshot screen capture 045 - magix cms i admin - www_magixcms_dev_admin_home_php_action edit edit 1](https://cloud.githubusercontent.com/assets/356674/16452418/aade269a-3e08-11e6-9831-9cb56ee12b25.png)


### Instructions
- Make sure you have FontAwesome loaded on the page that contains TinyMCE. 
- Copy the fontawesome folder into your TinyMCE plugins folder.
- Add this to your TinyMCE script:

    ```js
    tinymce.init({
        ...
        plugins: 'fontawesome'
        ...
        extended_valid_elements: '+span[*],+i[*]'
        ...
        toolbar: 'fontawesome';
        ...
		content_css: '//netdna.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css';
		...
    });
    ```
