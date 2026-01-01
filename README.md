# 3D Basic

3D Basic is a small, friendly programming language for creating 3D graphics and environments. It's designed for learning, experimentation, and rapid prototyping of 3D scenes with a minimal, easy-to-read syntax.

## Status
- Demo: A first working demo exists.
- Goal: Keep the language simple and approachable while enabling creation of interesting 3D scenes and basic interactivity.

## Demo & Documentation
- Live demo: https://misterekvall.wixsite.com/peter-ekvall-store/team-3-62
- Online manual: https://misterekvall.wixsite.com/peter-ekvall-store/team-3-51
- Example scenes: see the `examples/` folder

## Why 3D Basic?
- Minimal syntax aimed at beginners and artists
- Built-in primitives (cubes, spheres, planes), simple transforms, camera and lights
- Easy to extend with custom meshes and shaders
- Fast feedback loop for creative experimentation

## Vision
Imagine a programming language so simple, so intuitive, and so fun that anyone can create something amazing — no matter their age, experience, or background. That’s the dream behind 3D Basic.

I want to build a language where creativity comes first. A language where a child, with just two lines of code, can make something happen on the screen — and feel that magical little spark of excitement: "I made this!"

But this isn’t about clicking around in pre-made templates or dragging and dropping blocks. No, 3D Basic is about real programming — without being complicated. You get the feeling of building something from scratch, understanding what’s happening, and pointing to the screen with pride: "See that? That’s mine."

In today’s world, game development often feels like an exclusive club. People talk about complex engines, hundreds of files, advanced tools, and teams of twenty working day and night. But what if it didn’t have to be that way?

What if one curious person with a fun idea and a little spark in their eye could create something that makes others smile, laugh, or feel amazed? That’s the world I want to build.

With 3D Basic, the entry barrier to creativity is incredibly low. The first steps should feel easy, quick, and fun. The advanced features are there, but they stay hidden until you are ready for them. It should never feel like a tidal wave of complicated terms crashing over you. Instead, the journey begins with playfulness, curiosity, and the pure joy of creating.

And here’s the most exciting part:
When you get quick results — when you see something happen instantly — something magical happens inside you. You get energy. You get curious. You want to try more. You want to improve, explore, and push boundaries.

Suddenly, you find yourself sitting there, completely absorbed, and you realize you’ve learned so much — without even noticing.

That’s my vision.
A language where anyone, young or old, can turn ideas into reality.
A language where you can be a creator, not just a consumer.
A language that doesn’t just teach programming — it teaches the joy of creating.

3D Basic is the language I dreamed of as a kid.
A language that sparks imagination, builds confidence, and makes programming accessible to everyone.

## Example

- spinning cube (line-numbered style)

```
10 box1.size=(2,2,2)
20 box1.move=(0,1,0)
30 box1.animate.rotate=(0,0,0) to (0,360,0)
40 box1.draw
```

English explanation of the four lines:
- Line 10: Set the size of `box1` to 2×2×2.
- Line 20: Move `box1` to position (0, 1, 0).
- Line 30: Animate a rotation from (0,0,0) to (0,360,0) — a full Y-axis rotation.
- Line 40: Draw the box (render it / schedule it for rendering).

This demonstrates the core idea: very small programs that produce immediately visible 3D results.



## 3d Basic Window

![3d Basic Window](https://github.com/user-attachments/assets/b6d4c112-313d-4b45-8a71-072497088c60)



## Contact & Links

- Maintainer: Peter Ekvall (MisterPeterEkvall)
- Demo: https://misterekvall.wixsite.com/peter-ekvall-store/team-3-62
- Manual: https://misterekvall.wixsite.com/peter-ekvall-store/team-3-51


