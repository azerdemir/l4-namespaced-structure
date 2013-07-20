## A PSR-0 Namespaced Project Skeleton for Laravel

You can use this structure when initializing your Laravel projects.

### Project structure
![Project Structure](http://i44.tinypic.com/nv1gk1.jpg)

Default project structure reorganized as you can see in image.

composer.json contains "psr-0" autoloading for classes under src/ folder. Current level one namespace is
"Structure", you can change it, but don't forget to change the related line in compsoer.json and replace namespace and use statements in related controllers and models.

Also, you can create a new project from this skeleton like below:

    composer create-project azerdemir/l4-namespaced-structure new_project
