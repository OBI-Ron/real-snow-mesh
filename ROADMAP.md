# 🧭 Roadmap – Real Snow Mesh Blender Add-on

This roadmap outlines completed features and upcoming development priorities for the Real Snow Mesh Blender add-on. Contributions and feedback are encouraged and appreciated.

---

## ✅ Version 1.4 – Initial Modern Release
- ✅ Blender 4.3+ compatibility
- ✅ Overhauled material node tree to reflect Blender's modern shader pipeline
- ✅ Simplified UI and property management
- ✅ GitHub publishing and first public testing release
- ✅ Blender Artists feedback request posted

---

## 🔄 Planned for v1.5 – Material Options & Usability Improvements
- [ ] **External Material Option**  
  Allow importing a snow material from a packaged `.blend` file.
- [ ] **User-Customizable Snow Shader**  
  Load a user-edited snow material if it matches the expected name (`Snow`), enabling reuse.
- [ ] **No Material Option**  
  Allow generation of snow mesh without assigning any material at all.
- [ ] **Better Material Cleanup**  
  Clean up node trees and unused material slots to prevent clutter.

---

## 🌬️ Planned for v1.6 – Directional Snow Enhancements
- [ ] **Wind-Influenced Snow Placement**  
  Use an Empty object or user-defined vector to bias snow placement directionally.
- [ ] **Directional Gizmo**  
  In-viewport display of direction vector for clarity.
- [ ] **Face Culling Enhancements**  
  Improve how face normals are used to determine snow accumulation under directional bias.

---

## 🧪 Version 2.0 and Beyond – Experimental & Long-Term
- [ ] **Weight Paint Support**  
  Use vertex group or texture paint masks to influence snow density.
- [ ] **Snow Deformation Sculpting**  
  Procedural snow mounds or drifts for enhanced realism.
- [ ] **Physics-Based Accumulation (R&D)**  
  Early-stage idea: simulate snow fall, build-up, and melting using Blender's physics.

---

## 📬 Feedback & Contributions

📝 Got ideas or bugs? Use the links below:

- 💡 [Suggest a Feature](https://github.com/OBI-Ron/real-snow-mesh/issues/new?labels=enhancement&template=feature_request.md)
- 🐛 [Report a Bug](https://github.com/OBI-Ron/real-snow-mesh/issues/new?labels=bug&template=bug_report.md)
- 👨‍💻 [View or Contribute Code](https://github.com/OBI-Ron/real-snow-mesh)

---

## 🕒 Roadmap Update Policy

This document will be revised after major milestones, community feedback cycles, or Blender API changes. Follow the [Releases](https://github.com/OBI-Ron/real-snow-mesh/releases) page for official updates.

