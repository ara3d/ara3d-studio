# Ara 3D Studio

[**Ara 3D Studio**](https://github.com/ara3d/ara3d-studio/releases) is a free Windows desktop application for loading, viewing, 
and querying large 3D models. You can load GLB, GLTF, IFC, BOS, STL, OBJ, and GeoTIFF files. You can export binary glTF (.GLB) files 

The plugin and scripting ecosystem along with the geometry kernel and many core fetaures are built using the 
fully open-source and dependency free [Ara 3D SDK](https://github.com/ara3d/ara3d-sdk).

<img width="1280" height="720" alt="ara3d-viewer" src="https://github.com/user-attachments/assets/74af3d50-ba35-4113-b1ed-83c307ae69e4" />

| <sub>Thanks to <a href="https://www.cityweft.com/">Cityweft</a> for providing the test .GLB file of Montreal shown here</sub> |

---

## Status

- [Known Bugs](https://github.com/ara3d/ara3d-studio/issues?q=is%3Aissue%20state%3Aopen%20type%3ABug)
- [Planned Enhancements](https://github.com/ara3d/ara3d-studio/issues?q=is%3Aissue%20state%3Aopen%20type%3AImprovement)

---

## History

The latest and historical releases can be [found here]((https://github.com/ara3d/ara3d-studio/releases). 

Date | Version | Notes
--- | --- | ---
Jan 5 | v0.9.4 | Better performance, bundled with Revit .BOS exporter, GLB export 
Sept 12 | v0.9.3 | Performance improvements, and various small fixes and enhancements. 
Sept 3 | v0.9.2 | All dependencies seem to be present. First official beta! 
Sept 2 | v0.9.1 | Missing files, release was deleted.  
Aug 28 | v0.1 | Missing files, release was deleted.  

---

## Download & Install

- Get the latest builds on the **[Releases](https://github.com/ara3d/ara3d-studio/releases)** page.
- Supported OS: **Windows 10/11 (64-bit)**
- Download and run the latest ** *.Setup.exe **
- The default install location is `%localappdata%\Ara 3D\Ara 3D Studio\ara3d.exe`. 

If you have multiple GPUs, we suggest opening the Control Panel and choosing the GPU preference "High Performance" 
under `System > Display > Graphics`  

<img width="1020" height="490" alt="image" src="https://github.com/user-attachments/assets/457530df-2748-455d-b43a-ec0a705e4196" /> 

---

## About this repository

This repository hosts:
- [**Releases**](https://github.com/ara3d/ara3d-studio/releases) - for installers and portable builds
- [**Issues**](https://github.com/ara3d/ara3d-studio/issues) - for bugs, enhancements, and tasks.

---

## Privacy

Ara 3D Studio does **not** send any of your data off of your computer. 

---

## Features (current)

- Load common 3D formats: **glTF (GLB/GLTF), IFC, VIM, OBJ, STL, Collada (DAE)**
- Inspect and navigate large models interactively
- Run **C# scripts** via the open SDK
- Create **parametric geometry** and apply **parametric modifiers**

---

## Our vision

We aim to make AEC software as efficient and dependable as the projects it supports.  
Ara 3D Studio and the Ara 3D SDK apply modern software practices to large-scale geometry and data so you can explore, query, and validate models with less friction.

Our focus:
- **Performance:** handle large models smoothly on everyday hardware  
- **Interoperability:** work alongside existing authoring tools and open formats  
- **Extensibility:** a simple SDK for scripting, plug-ins, and custom workflows

---

## Troubleshooting

If Ara 3D Studio fails silently, or the main window never shows, try launching the application from the command prompt (cmd.exe) or using power shell. 
You will get a more useful error message.  

---

## FAQ

**Q: Why is this free?**  
Ara 3D Studio helps us validate the SDK and core algorithms with real projects. Making it free lowers the barrier to adoption, improves feedback loops, and grows the ecosystem that the SDK enables.

**Q: Why isn’t the app open-source?**  
Many of the most important components are open-source (see https://github.com/ara3d/ara3d-sdk).  
We keep the app closed to protect years of R&D and to ship a consistent, reliable experience. We keep the **SDK open** so anyone can build plug-ins, scripts, and integrations.

**Q: Who is it for?**  
Architects, engineers, BIM/VDC teams, researchers, and developers who need to load, inspect, and query large models efficiently.

**Q: Is this a replacement for authoring tools?**  
No. Ara 3D Studio is a **companion** for exploration, analysis, and validation. Keep using your authoring tools; use Ara 3D Studio to move faster when you need to inspect, query, or automate.

**Q: Can I use this at work?**  
Yes. It is free for commercial or personal use.

**Q: How does Ara 3D make money?**  
Through commercial services, libraries, integrations, and enterprise support built around the SDK and Studio.

---

## Support and Contribute

If you want to show your support for Ara 3D Studio please:
- Report issues with clear repro steps and files when possible
- Build plug-ins and scripts with the **[Ara 3D SDK](https://github.com/ara3d/ara3d-sdk)**  
- Suggest features and enhancements 
- Share feedback on workflows you’d like to streamline
- Share example datasets and workflows that stress real-world needs
- Tell colleagues who might benefit

---

## License

- **Ara 3D Studio:** proprietary, free to use for commercial or personal usage.
- **Ara 3D SDK:** open-source (MIT) — see the [SDK repo](https://github.com/ara3d/ara3d-sdk) for details
