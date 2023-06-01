[Skin Variations v0.1 by SioxerNikita]

Before you start adding the code, create your unit graphic. In your image, copy that and place it next to it, and make the variation you want.
Make sure that each "frame" fits within the same frame size.
If your unit has animation, make sure that each variation has all of its animation before you add the next variation.

Do note, this does not support scale animation on body.


1) in [core] add `copyFrom: ROOT:Oxidization Framework\Skin Variations\SkinVariations.copyFrom`

2) In [core] add `@copyFromSection: template_SKIN_Core`

3) in [core] add `@global: SKIN_VariationCount: 5`. The 5 is the amount of variations your unit has.

4) in [core] add `@global: SKIN_FramesPerVariation: 7`. The 7 is the amount of frames your unit graphic has. If it has no animation, put in 1.

5) in [core] add `@global: SKIN_FrameAnimation: 1`. The 1 means that it will use normal body animation ([graphics]animation as well as [animation]body_X), put 0 if you don't want it to use that.

6) Add [hiddenAction_SKIN] and add `@copyFromSection: template_SKIN_VariationInit` to it.

7) Add [decal_body] and add `@copyFromSection: template_SKIN_skinVariation` to it.

8) In [decal_body] add `image: YourBodyImage.png`, replace YourBodyImage.png with your image.

9) In [decal_body] add `frame_width: X` and `frame_width: Y`, being the size of your unit.

10) Profit
