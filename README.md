# Desiree
The Official desktop shell for Artemis. 

## Roadmap
The goal for Desiree is to be a desktop shell that is based on [weston](https://github.com/wayland-project/weston), and written in D. This will require a binding for libweston to D (which are not hard to create). As we start out, a static binding is easier to write and easier to understand, so my thoughts were to statically bind libweston to D as we need those API's. This project will be managed with dub.

If this gets far enough along, we'll probably create a separate repo for a dynamic binding of libweston to D, probably with some nice Object-oriented wrappers. We may even end up moving our static binding into a separate repo before we get very far. We'll see what is practical.

![Desiree Shell icon](Desiree%20Shell.png)
