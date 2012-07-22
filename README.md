Hippo-CMS-plugin-starting-point
===============================

Installation of this plugin in your project:

First, add:

```xml
<dependency>
  <groupId>org.onehippo.forge</groupId>
  <artifactId>myplugin-hst</artifactId>
  <version>1.00.00-SNAPSHOT</version>
</dependency>
```

to the pom.xml of your site module.

Then, add:

```xml
<dependency>
  <groupId>org.onehippo.forge</groupId>
  <artifactId>myplugin-cms</artifactId>
  <version>1.00.00-SNAPSHOT</version>
</dependency>
```

to the pom.xml of your cms module.

Finally, add:

```xml
<dependency>
  <groupId>org.onehippo.forge</groupId>
  <artifactId>myplugin-repository</artifactId>
  <version>1.00.00-SNAPSHOT</version>
</dependency>
```

to the pom.xml of your content module.