# Structure

1. Create a directory with a name of your shader (should be nameful)
2. Required files:

- `README.md`: Describes what it will render
- `fragment.code`: The actual shadercode. It should have the format of
- `demo.png` (or any other way to see the effect: A link to an image, a link to a video within in README is also fine): An image or video on how it looks like.

```
[[shader_code]]
Glsl = """
<glsl code>
"""
```

or

```
[[shader_code]]
Wgsl = """
<wgsl code>
"""
```

respectively. As an example you can take a look into one of your configs in `~/.config/vibe-daemon/output_configs`.
