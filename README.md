gwtphonegap-plugins
===================

This repository will wrap phonegap plugins to use with GWT (Google WebToolkit) and gwt-phonegap.

HOWTO
=====

In your module xml inherit following modules:

<inherits name="com.googlecode.gwtphonegap.PhoneGap"/>
<inherits name="com.googlecode.gwtphonegap.plugins.PhoneGapPlugins"/>

Instantiate the plugin with GWT.create();

Use it like it's described in the plugin interface:

For instance:

Facebook facebook = GWT.create(Facebook.class);
facebook.init(...);
...


PLANNED PLUGINS
===============
- PUSH-PLUGIN


You are welcome to introduce your own wrappers. Welcome are all plugins supported by phonegap-build.

