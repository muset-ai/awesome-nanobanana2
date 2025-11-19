# Reference Images

This directory is for storing reference images used in the prompt generation.

## Structure

For each case, reference images should be placed in the same directory as the case files:

```
cases/
  1/
    case.yml
    case.png              (generated result image)
    ref_emoji.png         (reference image 1)
    ref_design.png        (reference image 2)
  2/
    case.yml
    case.png
    ref_style.jpg         (reference image)
```

## Usage

In your `case.yaml`, list all reference images:

```yaml
reference_images:
  - ref_emoji.png
  - ref_design.png
```

Or if no reference images are needed, you can:
- Omit the field entirely
- Use an empty array: `reference_images: []`

## Naming Convention

Suggested naming patterns:
- `ref_<description>.png` - e.g., `ref_emoji.png`, `ref_style.jpg`
- Clear, descriptive names that indicate what the reference is for
