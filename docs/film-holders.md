# Film Holders

This document describes the film holder system used with the modular film scanning stand.

The holders are designed to keep the film flat, aligned and repeatable during camera scanning. Different holders can be used for 35mm film and medium format negatives such as 6x7 and 6x12.

## Design Goals

- Hold the film flat during scanning
- Keep the film plane repeatable
- Reduce reflections from the light source
- Allow accurate stitching of larger negatives
- Use simple 3D-printed parts
- Be easy to modify for different film formats

## Supported Formats

| Format | Notes |
|---|---|
| 35mm | Single-frame scanning |
| 6x7 | Medium format scanning |
| 6x12 | Stitched panoramic scanning |

## Holder Construction

The film holder consists of two main parts:

- a lower base part
- an upper clamping part

The lower part defines the film position and scanning window.  
The upper part holds the film down and helps keep it flat.

The two parts are aligned using metal pins.

## Alignment Pins

Metal pins are used to keep the film holder aligned between scans.

The first pair of pins defines the X-position.  
A second pair of pins helps control rotation while still allowing controlled tolerance in the Y-direction if needed.

This makes the holder repeatable while avoiding unnecessary stress on the printed parts or the film.

## Film Flatness

Film flatness is created by pressing the film between the upper and lower holder parts.

Screws can be used to apply light pressure.

The film should be held flat, but not so tightly that it scratches or bends.

## Scanning Window

The scanning window is smaller than the complete negative area in some holder versions.

This helps reduce unwanted reflections and improves contrast during scanning.

For stitched scans, the film can be scanned in multiple overlapping sections.

## 6x12 Scanning

The 6x12 holder is designed for stitched scanning.

Instead of capturing the whole negative in one image, the film is scanned in multiple overlapping shots. This allows higher resolution and better use of the camera sensor.

Typical workflow:

1. Place the film in the holder.
2. Align the first scanning position.
3. Capture the first image.
4. Move the camera or film holder to the next position.
5. Capture the overlapping image.
6. Repeat until the full negative is covered.
7. Stitch the images in software.

## Material

The holders are 3D printed.

Recommended materials:

- PETG
- ABS / ASA
- stiff carbon-filled filament

For this build, Extrudr GreenTEC Pro CF was used.

A matte black material is recommended to reduce reflections.

## Notes

Avoid glossy surfaces near the film or scanning window.

If reflections appear in the scan, reduce the window size, add matte black surfaces, or increase the distance between the film and reflective parts.

The holder design may need to be adjusted depending on the exact light source, camera setup and scanning format.
