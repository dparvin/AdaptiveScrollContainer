## ✨ AdaptiveScrollContainer Overview

**AdaptiveScrollContainer** is a cross-platform container control that dynamically adapts its layout behavior based on available space.

- 🧱 **Acts like a normal container** until a defined transition point.
- 🖱️ **Scrollbars appear** when the container becomes smaller than the specified threshold.
- ⚡ **Smart focus handling:** Automatically scrolls to keep the control with focus visible.
- 📐 **Supports nested containers** — each can have independent adaptive behavior.
- 🧍 **Cross-platform roadmap:** WinForms → WPF → MAUI (iOS + Android + Windows + macOS) → Web (and possibly others).

---

## 🧭 Project Structure

| Project | Description |
|:---------|:-------------|
| `src/AdaptiveScrollContainer.WinForms` | Core WinForms control library |
| `src/AdaptiveScrollContainer.WPF` | Core WPF control library |
| `src/AdaptiveScrollContainer.WinForms.Runner` | Manual test harness for WinForms (interactive design & behavior testing) |
| `src/AdaptiveScrollContainer.WPF.Runner` | Manual test harness for WPF |
| `tests/AdaptiveScrollContainer.WinForms.Test` | Automated xUnit test suite for WinForms |
| `tests/AdaptiveScrollContainer.WPF.Test` | Automated xUnit test suite for WPF |

---

## 🧩 Development Roadmap

### Phase 1 — 🪟 WinForms Foundation
- [x] Repository initialization
- [x] WinForms solution/project structure
- [ ] Implement adaptive layout behavior
- [ ] Handle scrollbar activation logic
- [ ] Maintain focus visibility on scroll
- [ ] Add nested container support
- [ ] Add unit tests for adaptive thresholds
- [ ] Complete sample UI in **WinForms.Runner**

### Phase 2 — 🪟 WPF Implementation
- [x] WPF project structure and runner created
- [ ] Port adaptive behavior to WPF layout system
- [ ] Support logical scrolling & focus tracking
- [ ] Add WPF-specific visual states (e.g., smooth transitions)
- [ ] Add test coverage in **WPF.Test**
- [ ] Demonstrate cross-framework behavior parity

### Phase 3 — 📱 MAUI Expansion (iOS + Android + macOS + Windows)
- [ ] Define shared adaptive layout abstractions
- [ ] Prototype adaptive layout using MAUI layout system
- [ ] Validate touch/gesture-based scrolling on iOS & Android
- [ ] Add MAUI.Runner and MAUI.Test projects
- [ ] Ensure consistent behavior across all device form factors

### Phase 4 — 🌐 Web & Other Platforms
- [ ] Investigate web implementation (e.g., Blazor or JavaScript component)
- [ ] Design platform-neutral adaptive logic for reuse
- [ ] Implement Rust / cross-language prototype (optional)

### Phase 5 — 📦 Packaging & Distribution
- [ ] Consolidate shared logic into a `AdaptiveScrollContainer.Shared` project
- [ ] Create NuGet packaging project
- [ ] Multi-target all currently supported .NET versions
- [ ] Generate XML docs and README-based documentation
- [ ] Publish to NuGet and GitHub Packages

---

## 🧱 Vision

AdaptiveScrollContainer aims to provide a **unified adaptive layout model** across frameworks; 
allowing developers to design rich, responsive, and usable interfaces that automatically adjust when screen real estate becomes limited, without sacrificing design quality or usability.

---
