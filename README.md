R:\xd\MnM+Adventure_hf+Serverpack>java -Xmx9216M -Xms9216M -jar forge-1.16.5-36.2.19.jar nogui
2022-08-10 11:03:13,047 main WARN Advanced terminal features are not available in this environment
[11:03:13] [main/INFO] [cp.mo.mo.Launcher/MODLAUNCHER]: ModLauncher running: args [--gameDir, ., --launchTarget, fmlserver, --fml.forgeVersion, 36.2.19, --fml.mcpVersion, 20210115.111550, --fml.mcVersion, 1.16.5, --fml.forgeGroup, net.minecraftforge, nogui]
[11:03:13] [main/INFO] [cp.mo.mo.Launcher/MODLAUNCHER]: ModLauncher 8.0.9+86+master.3cf110c starting: java version 1.8.0_321 by Oracle Corporation
[11:03:13] [main/INFO] [ne.mi.fm.lo.FixSSL/CORE]: Added Lets Encrypt root certificates as additional trust
[11:03:13] [main/INFO] [mixin/]: SpongePowered MIXIN Subsystem Version=0.8.4 Source=file:/R:/xd/MnM+Adventure_hf+Serverpack/libraries/org/spongepowered/mixin/0.8.4/mixin-0.8.4.jar Service=ModLauncher Env=SERVER
[11:03:14] [main/INFO] [STDERR/]: [org.antlr.v4.runtime.ConsoleErrorListener:syntaxError:38]: line 2:141 token recognition error at: ';'
[11:03:14] [main/INFO] [STDERR/]: [org.antlr.v4.runtime.ConsoleErrorListener:syntaxError:38]: line 2:141 token recognition error at: ';'
[11:03:14] [main/INFO] [STDERR/]: [org.antlr.v4.runtime.ConsoleErrorListener:syntaxError:38]: line 4:60 token recognition error at: ';'
[11:03:15] [main/INFO] [STDERR/]: [org.antlr.v4.runtime.ConsoleErrorListener:syntaxError:38]: line 1:0 token recognition error at: '~'
Init EnhancedVisuals coremods ...
Init CreativeCore coremods ...
[11:03:15] [main/ERROR] [mixin/]: Mixin config illagers_plus.mixin.json does not specify "minVersion" property
Exception in thread "main" [11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]: java.lang.NoSuchMethodError: sun.security.util.ManifestEntryVerifier.<init>(Ljava/util/jar/Manifest;)V
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at cpw.mods.modlauncher.SecureJarHandler.createCodeSource(SecureJarHandler.java:66)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at cpw.mods.modlauncher.TransformingClassLoader$DelegatedClassLoader.findClass(TransformingClassLoader.java:275)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at cpw.mods.modlauncher.TransformingClassLoader.loadClass(TransformingClassLoader.java:136)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at cpw.mods.modlauncher.TransformingClassLoader.loadClass(TransformingClassLoader.java:98)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at java.lang.ClassLoader.loadClass(Unknown Source)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at java.lang.Class.forName0(Native Method)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at java.lang.Class.forName(Unknown Source)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at org.spongepowered.asm.service.modlauncher.ModLauncherClassProvider.findClass(ModLauncherClassProvider.java:67)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at org.spongepowered.asm.launch.platform.MixinConnectorManager.loadConnectors(MixinConnectorManager.java:70)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at org.spongepowered.asm.launch.platform.MixinConnectorManager.inject(MixinConnectorManager.java:59)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at org.spongepowered.asm.launch.platform.MixinPlatformManager.inject(MixinPlatformManager.java:196)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at org.spongepowered.asm.launch.MixinBootstrap.inject(MixinBootstrap.java:202)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at org.spongepowered.asm.launch.MixinLaunchPluginLegacy.initializeLaunch(MixinLaunchPluginLegacy.java:201)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at org.spongepowered.asm.launch.MixinLaunchPluginLegacy.initializeLaunch(MixinLaunchPluginLegacy.java:195)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at cpw.mods.modlauncher.LaunchPluginHandler.lambda$announceLaunch$9(LaunchPluginHandler.java:97)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at java.util.HashMap.forEach(Unknown Source)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at cpw.mods.modlauncher.LaunchPluginHandler.announceLaunch(LaunchPluginHandler.java:97)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:52)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:72)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at cpw.mods.modlauncher.Launcher.run(Launcher.java:82)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at cpw.mods.modlauncher.Launcher.main(Launcher.java:66)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at net.minecraftforge.server.ServerMain$Runner.runLauncher(ServerMain.java:63)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at net.minecraftforge.server.ServerMain$Runner.access$100(ServerMain.java:60)
[11:03:15] [main/INFO] [STDERR/]: [java.lang.ThreadGroup:uncaughtException:-1]:         at net.minecraftforge.server.ServerMain.main(ServerMain.java:57)

R:\xd\MnM+Adventure_hf+Serverpack>pause
