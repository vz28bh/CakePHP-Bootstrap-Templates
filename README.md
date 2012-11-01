CakePHP-Bootstrap-Templates
===========================

Templates for baking BootStrap compatible views in CakePHP

Put this folder in your app\Console\Template\default and copy the actions and classes folder from the Cake\Console\Templates\default folder, too.

Now when you bake that app you will get custom views that make a reasonably decent Bootstrap app.

Use the default.ctp layout file as a good starting point.

Make sure you provide the Jquery and Bootstrap files that are needed.  In the provided layout you can see the necessary files

```
echo $this->Html->css('bootstrap-responsive');
echo $this->Html->script('jquery-1.7.2.min');
echo $this->Html->script('bootstrap');
```

Update as necessary with the versions you prefer.