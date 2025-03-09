# Structure

1. Create a directory with a name of your shader (should be nameful)
2. The directory must include:

- a `README.md` with:
  - enough information on what the shader produces (by using an image/video)
  - don't forget to give credits (and ask for permission if needed) to the original creator if you are using it from somewhere else!
  - templates are below
- `code.toml` which contains the shader code in the following format:
  ```
  [shader_code]
  Glsl = """
  <your glsl code>
  """
  ```
  for `glsl` or
  ```
  [shader_code]
  Wgsl = """
  <your wgsl code>
  """
  ```
  for wgsl
