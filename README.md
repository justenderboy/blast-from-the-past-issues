# blast-from-the-past-issues
java.lang.IllegalArgumentException: Failed to create model for minecraft:sniffer
	at net.minecraft.client.renderer.entity.EntityRenderers.m_257087_(EntityRenderers.java:164) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:goety.mixins.json:EntityRenderersMixin,pl:mixin:A}
	at java.util.HashMap.forEach(HashMap.java:1429) ~[?:?] {re:mixin}
	at net.minecraft.client.renderer.entity.EntityRenderers.m_174049_(EntityRenderers.java:160) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:goety.mixins.json:EntityRenderersMixin,pl:mixin:A}
	at net.minecraft.client.renderer.entity.EntityRenderDispatcher.m_6213_(EntityRenderDispatcher.java:360) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:playerAnimator-common.mixins.json:firstPerson.EntityRenderDispatcherMixin,pl:mixin:APP:entity_model_features-common.mixins.json:accessor.EntityRenderDispatcherAccessor,pl:mixin:APP:entity_model_features-common.mixins.json:rendering.MixinEntityRenderDispatcher,pl:mixin:APP:entity_texture_features-common.mixins.json:entity.misc.MixinEntityRenderDispatcher,pl:mixin:APP:species.mixins.json:client.EntityRenderDispatcherMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.server.packs.resources.ResourceManagerReloadListener.m_10759_(ResourceManagerReloadListener.java:15) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:classloading,re:mixin}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:787) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,re:classloading,pl:mixin:APP:blueprint.mixins.json:SimpleReloadInstanceMixin,pl:mixin:A}
	at net.minecraft.util.thread.BlockableEventLoop.m_6367_(BlockableEventLoop.java:156) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.util.thread.ReentrantBlockableEventLoop.m_6367_(ReentrantBlockableEventLoop.java:23) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,re:computing_frames,re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.m_7245_(BlockableEventLoop.java:130) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.util.thread.BlockableEventLoop.m_18699_(BlockableEventLoop.java:115) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1106) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:718) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[1.20.1-forge-47.3.10.jar:?] {re:classloading,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.DirectMethodHandleAccessor.invoke(DirectMethodHandleAccessor.java:103) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:580) ~[?:?] {re:mixin}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.3.10.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.3.10.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.3.10.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}
Caused by: java.lang.IllegalArgumentException: No model for layer snifferplus:sniffer#saddle
	at net.minecraft.client.model.geom.EntityModelSet.m_171103_(EntityModelSet.java:17) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:A}
	at net.minecraft.client.renderer.entity.EntityRendererProvider$Context.m_174023_(EntityRendererProvider.java:63) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,re:classloading}
	at net.minecraft.client.renderer.entity.SnifferRenderer.handler$boe000$snifferplus_addSaddleLayer(SnifferRenderer.java:528) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,re:classloading,pl:mixin:APP:snifferplus.mixins.json:MixinSnifferRenderer,pl:mixin:A}
	at net.minecraft.client.renderer.entity.SnifferRenderer.<init>(SnifferRenderer.java:14) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,re:classloading,pl:mixin:APP:snifferplus.mixins.json:MixinSnifferRenderer,pl:mixin:A}
	at net.minecraft.client.renderer.entity.EntityRenderers.m_257087_(EntityRenderers.java:162) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:goety.mixins.json:EntityRenderersMixin,pl:mixin:A}
	... 27 more


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Render thread
Suspected Mod: 
	Hellion's Sniffer+ (snifferplus), Version: 0.3.0
		Issue tracker URL: https://github.com/Dariensg/Hellions-Sniffer-Plus/issues
		Mixin class: com.helliongames.snifferplus.mixin.MixinSnifferRenderer
		Target: net.minecraft.client.renderer.entity.SnifferRenderer
		at TRANSFORMER/minecraft@1.20.1/net.minecraft.client.renderer.entity.SnifferRenderer.handler$boe000$snifferplus_addSaddleLayer(SnifferRenderer.java:528)
Stacktrace:
	at net.minecraft.client.renderer.entity.EntityRenderers.m_257087_(EntityRenderers.java:164) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:goety.mixins.json:EntityRenderersMixin,pl:mixin:A}
	at java.util.HashMap.forEach(HashMap.java:1429) ~[?:?] {re:mixin}
	at net.minecraft.client.renderer.entity.EntityRenderers.m_174049_(EntityRenderers.java:160) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:goety.mixins.json:EntityRenderersMixin,pl:mixin:A}
	at net.minecraft.client.renderer.entity.EntityRenderDispatcher.m_6213_(EntityRenderDispatcher.java:360) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:playerAnimator-common.mixins.json:firstPerson.EntityRenderDispatcherMixin,pl:mixin:APP:entity_model_features-common.mixins.json:accessor.EntityRenderDispatcherAccessor,pl:mixin:APP:entity_model_features-common.mixins.json:rendering.MixinEntityRenderDispatcher,pl:mixin:APP:entity_texture_features-common.mixins.json:entity.misc.MixinEntityRenderDispatcher,pl:mixin:APP:species.mixins.json:client.EntityRenderDispatcherMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.server.packs.resources.ResourceManagerReloadListener.m_10759_(ResourceManagerReloadListener.java:15) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:classloading,re:mixin}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:787) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,re:classloading,pl:mixin:APP:blueprint.mixins.json:SimpleReloadInstanceMixin,pl:mixin:A}
	at net.minecraft.util.thread.BlockableEventLoop.m_6367_(BlockableEventLoop.java:156) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
	at net.minecraft.util.thread.ReentrantBlockableEventLoop.m_6367_(ReentrantBlockableEventLoop.java:23) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,re:computing_frames,re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.m_7245_(BlockableEventLoop.java:130) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,re:computing_frames,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B}
-- Overlay render details --
Details:
	Overlay name: net.minecraftforge.client.loading.ForgeLoadingOverlay
Stacktrace:
	at net.minecraft.client.renderer.GameRenderer.m_109093_(GameRenderer.java:957) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:moonlight-common.mixins.json:GameRendererMixin,pl:mixin:APP:blastfromthepast.mixins.json:client.GameRendererMixin,pl:mixin:APP:entity_model_features-common.mixins.json:MixinGameRenderer,pl:mixin:APP:alexscaves.mixins.json:client.GameRendererMixin,pl:mixin:APP:zeta_forge.mixins.json:client.GameRenderMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1146) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:718) ~[client-1.20.1-20230612.114412-srg.jar%23320!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[1.20.1-forge-47.3.10.jar:?] {re:classloading,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.DirectMethodHandleAccessor.invoke(DirectMethodHandleAccessor.java:103) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:580) ~[?:?] {re:mixin}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.3.10.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.3.10.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.3.10.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}
