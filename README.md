EzAnimation.ue4
====

Easing/Animation plugin for UnrealEngine4

![b](ball.gif)<br>
__ByBlueprint__
<img src="ball_bp.png" width="400px" /><br>

__ByCode__
```cpp
auto ctx = UEzAnimationFunctionLibrary::FadeInWithScale(
  staticMeshComponent,
  2.0f /* duration */, 1.0f /* targetScale */,
  EzEaseType::EaseElasticOut);
ctx->AppendDestroy();
```
