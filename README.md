# Operating systems
- http://blog.developpez.com/cpcdososx/p12295/non-classe/creer-mon-propre-os-avec-cpcdos-osx

## Assembly, GDT and protected mode
- http://esauvage.developpez.com/tutoriels/asm/assembleur-intel-avec-nasm/?page=page_8#LVIII.4
- http://www.asmfr.com/forum/sujet-VESA-MODE-PROTEGE_1011138.aspx?p=2
- https://github.com/neonics/qure/blob/master/DOC/Specs/VBE-AF07.pdf (and other documents in qure's git repository)
- http://michelizza.developpez.com/realiser-son-propre-systeme/
 
## drivers
- lib for building safe device drivers in C : http://code.google.com/p/rathaxes/ -> port in java for JNode ?

# Java Virtual Machine
- discussion : http://stackoverflow.com/questions/3887130/java-implementation-of-a-jvm
- Squawk (http://en.wikipedia.org/wiki/Squawk_virtual_machine) no need of an operating system to run, unlike Maxine VM (https://wikis.oracle.com/display/MaxineVM/VM+Internals)
- Maxine Virtual Edition - Maxine on Xen : http://kenai.com/projects/guestvm/sources/guk/show
 
porter Squawk : http://java.net/projects/squawk/pages/BuildingSquawkForOtherMCUs

# raspberry pi
- arkos (Os pour raspberry) : http://www.techworld.com.au/article/528273/arkos_building_anti-cloud_raspberry_pi_/
- OpenHAB Home Automation on Raspberry Pi : http://javacodegeeks.tradepub.com/free/w_make215/prgm.cgi
- Building a Media Center with Raspberry Pi : http://javacodegeeks.tradepub.com/free/w_pacb35/prgm.cgi

# Animation
- trident, anim lib for java : https://github.com/kirill-grouchnikov/trident
- java-universal-tween-engine : http://code.google.com/p/java-universal-tween-engine/
- http://www.aurelienribon.com/blog/
- http://jtoaster.sourceforge.net/

# Physics
- http://jmonkeyengine.org/ (hello_physics : https://jmonkeyengine.github.io/wiki/jme3/beginner/hello_physics.html)
- http://code.google.com/p/jinngine/source/browse/trunk/
- http://jbullet.advel.cz/
- http://code.google.com/p/dyn4j/
- http://www.jbox2d.org/
- Android game : http://libgdx.badlogicgames.com/showentry.html?id=apparatus

# Event libraries
- http://docs.guava-libraries.googlecode.com/git/javadoc/com/google/common/eventbus/package-summary.html
- http://code.google.com/p/guava-libraries/wiki/EventBusExplained
- http://code.google.com/p/simpleeventbus/
- http://code.google.com/p/javaeventing/
- http://www.eventbus.org/api/index.html

# Git
- Git rebase workflow : https://randyfay.com/content/rebase-workflow-git

## Git bisect
- http://stackoverflow.com/questions/29300194/create-new-junit-test-and-run-with-git-bisect
- https://www.javacodegeeks.com/2014/03/automated-bug-finding-with-git-bisect-and-mvn-test.html

## Git process
- http://nvie.com/posts/a-successful-git-branching-model/
- outil : http://jeffkreeftmeijer.com/2010/why-arent-you-using-git-flow/
- https://github.com/nvie/gitflow/wiki/Windows

## git encoding
- http://man.he.net/man1/git-commit
- http://code.google.com/p/msysgit/issues/detail?id=369
- https://groups.google.com/forum/?fromgroups#!topic/msysgit/n5QvcOUDjy8
   
## gitblit
- http://gitblit.com/setup.html

## git and java
- jgitflow (git-flow in java, based on JGit) : https://bitbucket.org/atlassian/jgit-flow/wiki/using-jgitflow-as-a-library
- maven + git-flow (based on jgitflow) : https://bitbucket.org/atlassian/maven-jgitflow-plugin
- git-flow for IDEA : https://github.com/pbuda/gitflowidea
- JGit examples : http://stackoverflow.com/questions/6861881/jgit-cannot-find-a-tutorial-or-simple-example, https://github.com/kevinsawicki/gitective 

# Testing
- Pairs-testing : http://code.google.com/p/jwise/source/browse/trunk/jwise/test/core/PairTest.java, http://code.google.com/p/jcombinatorial/
- JUnit ParameterSupplier : http://blog.schauderhaft.de/2010/02/07/junit-theories/

# Ideas for personal projects (their names at end of line between parenthesis)
- filechooser for VFS : vfsjfilechooser (no more maintained) and its 2 forks http://code.google.com/p/vfsjfilechooser2/, http://code.google.com/p/otrosvfsbrowser/ (safe / desktop)
- https://github.com/aeremenok/swing-formbuilder (safe / desktop)
- https://github.com/eikek/swing-tasks (desktop)
- http://supercsv.sourceforge.net/ (safe)
- http://sojo.sourceforge.net/index.html
- http://jodd.org/doc/methref.html + autres outils/librairies de jodd (safe / desktop)
- http://docs.oracle.com/javase/tutorial/extra/fullscreen/example.html (full screen) (desktop)
- http://brandonborkholder.github.com/glg2d/apidocs/index.html (acceleration graphics2D avec opengl) (desktop)
- http://emblemparade.net/projects/vncj/
- cacio-tta : http://ramshacking.blogspot.fr/2009/07/server-class-for-vnc.html
- http://emblemparade.net/projects/javaurl/architecture.html (desktop)

# Transformation librairies
- A voir en premier : http://morph.sourceforge.net/reference/html/transformers.html#transformers-graphs
- EzMorph and related projects : http://ezmorph.sourceforge.net/
     
# java performance
- http://java-performance.com/
- http://blog.jooq.org/2015/02/05/top-10-easy-performance-optimisations-in-java/
- http://www.rapidoid.org/

# maven + tomcat
- http://www.mkyong.com/maven/how-to-deploy-maven-based-war-file-to-tomcat/
- http://www.javacreed.com/how-to-run-embedded-tomcat-with-maven/

# builder generators
- http://www.vineetmanohar.com/2009/11/3-ways-to-run-java-main-from-maven/
- https://github.com/uglycustard/buildergenerator

# Ideas :
- use Window.getWindows() (Frame.getFrames() ?) in desktop project
- To dowload third party libraries, in JNode plugin list : maven:junit:junit:4.2 (or maven-alias:junit to centralize artifacts) -> convertor from pom.xml to JNode plugin's xml

# Others
- Open source CMS in java : http://www.ametys.org/fr/index.html
- Plugin architecture : http://blog.nuclex-games.com/tutorials/cxx/plugin-architecture/
- https://code.google.com/p/proteus-framework/
- http://www.developpez.com/actu/47473/Codename-One-la-boite-a-outils-Java-open-source-pour-le-developpement-mobile-multiplateforme-sur-une-base-de-code-unique-sort/
- http://www.codenameone.com/ 
- http://neomades.com/
- http://lwuit.java.net/
- https://github.com/twillouer/assertj-assertions-generator-idea
- Simplified crypto : http://www.jasypt.org/index.html
- JCI (java compiler interface) : http://commons.apache.org/proper/commons-jci/
- a pure java alternative for html renderer flying soccer : http://djproject.sourceforge.net/ns/
- microcloud with gridgain : http://www.gridgain.com/blog/archives/micro-cloud-in-your-jvm-code-example/
- http://www.smardec.com/products/mouse-gestures.html
- http://commons.apache.org/exec/apidocs/org/apache/commons/exec/DefaultExecutor.html
- shrinkwrap (obtain an archive from a maven repo) : https://community.jboss.org/message/600241?_sscc=t
- license : http://maven.apache.org/plugins/maven-project-info-reports-plugin/license-mojo.html
- IOC-Container : https://github.com/kevinpollet/IOC-Container
- Java process builder : http://code.google.com/p/jlibs/wiki/JavaProcessBuilder
- Design of an API, VisualVM, jdk performance : http://fr.slideshare.net/drorbr/jdk-tools-for-performance-diagnostics-2932301
- neural network : http://simbrain.net/index.html
- bhava-wheel : http://code.google.com/p/bhava-wheel/
- http://stackoverflow.com/questions/702535/using-maven-from-ant
- https://github.com/github/choosealicense.com
- swing rendering offscreen : http://stackoverflow.com/questions/2908418/rendering-swing-components-to-an-offscreen-buffer
- xsd validation : http://stackoverflow.com/questions/15732/whats-the-best-way-to-validate-an-xml-file-against-an-xsd-file

==========================

Tips :
- sign an android application : http://developer.android.com/guide/publishing/app-signing.html#releasecompile
keytool -list -storetype pkcs12 -keystore "Android Mobilis.p12"
jarsigner -storetype pkcs12 -keystore "Android Mobilis.p12" MVola.apk "android ideo mobilis"

- Full screen on clic on an image : http://stackoverflow.com/questions/4915312/making-image-full-screen-on-android-tutorial-app
- async task (with robotguice) : http://code.google.com/p/roboguice/wiki/RoboAsyncTask
- maven & android : http://code.google.com/p/maven-android-plugin/wiki/GettingStarted
- listview avec vue specific pour items : http://www.ace-art.fr/wordpress/2010/07/21/tutoriel-android-partie-6-les-listview/
- http://code.google.com/p/dynadroid/source/browse/trunk/java/src/org/dynadroid/utils/CrashHandler.java
- http://www.droidfonts.com/info/droid-serif-fonts/

- http://www-igm.univ-mlv.fr/~forax/ens/java-avance/cours/pdf/10-%20Concurrency.pdf
- http://developer.android.com/reference/android/app/ListFragment.html
- http://developerlife.com/tutorials/?p=327
- http://android-er.blogspot.com/2010/07/load-listview-in-background-asynctask.html
- http://android-developers.blogspot.com/2010/07/multithreading-for-performance.html
- http://commonsware.com/blog/
- http://code.google.com/p/shelves/source/browse/trunk/Shelves/src/org/curiouscreature/android/shelves/drawable/SpotlightDrawable.java
- http://developer.android.com/reference/android/os/Debug.html
- https://github.com/commonsguy
- https://sites.google.com/site/androidcontentfromchet/downloads/UITipsTricksTechniques.pdf?attredirects=1
- http://nookdevs.com/Emulator

- http://www.android2ee.com/index.php?option=com_content&view=article&id=87&Itemid=155&lang=fr
- http://www.vogella.de/articles/AndroidPerformance/article.html
- http://www.javacodegeeks.com/2012/01/wizard-design-pattern.html

- plusieurs fenetre dans android : http://www.onskreen.com/cornerstone/
- choisir une licence : http://www.zdnet.com/blog/burnette/howto-pick-an-open-source-license-part-1/130
- async swing : http://weblogs.java.net/blog/forax/archive/2011/10/01/asyncswing

- framework "à la grails" (cad findByName & co) mais avec des API Java : http://activeobjects.java.net/0.8.2/api/overview-summary.html

- JCL (Java ClassLoader) : http://kamranzafar.github.io/JCL/ 

# tomcat & timeouts
- https://tomcat.apache.org/tomcat-7.0-doc/config/http.html
- https://tomcat.apache.org/connectors-doc/common_howto/timeouts.html

# compilation
- https://github.com/google/compile-testing
- https://github.com/rhulha/anty4j/blob/master/Anty/src/com/googlecode/anty4j/Anty.java

- Effective TypeSafe config : http://www.janvsmachine.net/2016/07/effective-typesafe-config.html

# Download file REST & proxy
- https://docs.jboss.org/resteasy/docs/3.0-beta-3/userguide/html/RESTEasy_Client_Framework.html
- http://io-tools.sourceforge.net/easystream/apidocs/index.html http://stackoverflow.com/questions/29712554/how-to-download-a-file-using-a-java-rest-service-and-a-data-stream
- http://stackoverflow.com/questions/3496209/input-and-output-binary-streams-using-jersey
- http://jodd.org/doc/proxetta/invocation-replacement.html
