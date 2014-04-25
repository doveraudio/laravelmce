#A simple package to add **TinyMCE** to a **laravel** project.

use composer, and add the following line to your composer under "require"

    "jleach/laravelmce": "dev-master"


then add this line to your head section in your html page.

    {{ HTML::script('packages/jleach/laravelmce/js/tinymce/tinymce.min.js') }}


    tinymce.init({
        selector: "textarea"
    });
 
 and in the body:
 
    <form method="post">
    <textarea></textarea>
    </form>
