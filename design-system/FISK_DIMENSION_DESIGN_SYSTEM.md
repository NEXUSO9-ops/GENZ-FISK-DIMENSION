# FISK DIMENSION × OMEGA-9 — Canonical Visual System

## 📜 Design Philosophy

The Fisk Dimension visual identity embodies **sovereign authority, cosmic intelligence, and architectural permanence**. It unifies three complementary motifs into a cohesive system that communicates command hierarchy, system integrity, and celestial majesty.

### Core Principles
- **Precision**: Every element has deliberate placement and purpose
- **Hierarchy**: Strong focal dominance with accessible contrast
- **Restraint**: No decorative clutter; effects serve function
- **Consistency**: Reusable patterns across all applications
- **Security**: Visual distinction of system states without relying on color alone

---

## 🎨 Color System

### Primary Palette
| Name | Hex | Usage | CSS Variable |
|------|-----|-------|--------------|
| Obsidian Black | `#0A0A0F` | Primary backgrounds, deep surfaces | `--fisk-obsidian` |
| Midnight Navy | `#0F172A` | Secondary backgrounds, panels | `--fisk-navy` |
| Ice White | `#F8F9FA` | Primary text, surfaces | `--fisk-ice` |
| Electric Cyan | `#00D4FF` | Primary accents, connectors | `--fisk-cyan` |
| Deep Sapphire | `#1E3A8A` | Secondary accents, depth | `--fisk-sapphire` |
| Restrained Violet | `#6366F1` | Tertiary accents, highlights | `--fisk-violet` |
| Antique Gold | `#D4AF37` | Metallic details, crowns, borders | `--fisk-gold` |

### Governance Palette (Documents & Infographics Only)
| Name | Hex | Usage |
|------|-----|-------|
| Ivory | `#FFFFF0` | Document backgrounds |
| Pale Blue | `#E0F2FE` | Presentation surfaces |

### Semantic States
| State | Primary | Secondary | Symbol | Usage |
|-------|---------|-----------|--------|-------|
| Verified | `#00D4FF` | `#0099CC` | ✓ Circle | Confirmed, audited, secure |
| Reported | `#6366F1` | `#4F46E5` | △ Triangle | User-submitted, unconfirmed |
| Pending | `#D4AF37` | `#B8860B` | ⏳ Hourglass | In progress, awaiting |
| Blocked | `#EF4444` | `#DC2626` | □ Square | Denied, restricted |
| Failed | `#7C2D12` | `#591F0A` | ✗ X | Error, broken, invalid |

### Color Usage Rules
- **Never use color alone** to convey status — always pair with symbols
- **Cyan lines** connect elements; width: 1-2px maximum
- **Gold** used sparingly for metallic/highlight details
- **Violet** for interactive elements and active states
- **Sapphire** for depth and secondary information

---

## 🏗 Geometric Foundation

### Spacing System
```
4px  – xs (micro spacing)
8px  – sm (tight elements)
16px – md (standard padding)
24px – lg (panel margins)
32px – xl (section separation)
48px – 2xl (major divisions)
64px – 3xl (hero spacing)
96px – 4xl (section headers)
128px – 5xl (page margins)
```

### Border Radius
```
2px  – sharp (technical elements)
4px  – subtle (panels, cards)
8px  – standard (containers)
16px – soft (dialogs, modals)
```

### Stroke Widths
```
1px – connectors, dividers
2px – borders, frames
3px – emphasis borders
4px – heavy dividers
```

### Typography
**Primary Font Stack:**
```css
font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
```

**Weights:**
- 300 (Light) – Subtle labels, captions
- 400 (Regular) – Body text
- 500 (Medium) – Emphasis, buttons
- 600 (SemiBold) – Headers, titles
- 700 (Bold) – Section headers, important

**Scale:**
```
12px / 0.75rem – Caption
14px / 0.875rem – Small text
16px / 1rem – Body
18px / 1.125rem – Large body
20px / 1.25rem – Subheader
24px / 1.5rem – Header
32px / 2rem – Section header
48px / 3rem – Page header
64px / 4rem – Hero display
```

---

## 🦁 Motif 1: Regal Sentinel

### Concept
A majestic white lion embodying **authority, protection, and wisdom**. The sentinel watches over the Fisk Dimension with calm vigilance.

### Visual Specifications
- **Silhouette**: Recognizable lion profile, upright posture
- **Mane**: Flowing white-silver, geometric patterns
- **Eyes**: Icy cyan (#00D4FF) with subtle glow
- **Crown**: Antique gold (#D4AF37) with deep sapphire (#1E3A8A) jewels
- **Expression**: Calm, protective, slightly forward gaze
- **Style**: Clean vector, minimal detail, geometric precision

### Usage
- Primary logo element
- Watermark patterns
- Security badges
- Command authority indicators

### Variations
1. **Full Figure**: Complete lion with crown, seated or standing
2. **Profile**: Side view, head and shoulders
3. **Head Only**: Crowned head for icons
4. **Silhouette**: Solid black/white for subtle applications
5. **Wireframe**: Gold outline for technical contexts

### SVG Files
- `motifs/regal-sentinel-full.svg` – Complete figure
- `motifs/regal-sentinel-profile.svg` – Side profile
- `motifs/regal-sentinel-head.svg` – Head only
- `motifs/regal-sentinel-silhouette.svg` – Minimal silhouette

---

## 🧠 Motif 2: Holographic Intelligence

### Concept
A luminous abstract presence representing **system intelligence, neural processing, and data flow**. Subtle, controlled, and precise.

### Visual Specifications
- **Core**: Concentric rings suggesting audio signals/scan lines
- **Neural Structure**: Delicate cyan-blue lines, hexagonal patterns
- **Light**: Controlled glow, no excessive neon
- **Geometry**: Precise circles, hexagons, thin connectors
- **Color**: Cyan primary (#00D4FF), violet secondary (#6366F1)

### Components
1. **Signal Rings**: 3-4 concentric circles, 1px cyan stroke
2. **Neural Web**: Interconnected nodes with thin cyan lines
3. **Core Pulse**: Subtle radial gradient from cyan to transparent
4. **Data Points**: Small dots along connection paths

### Usage
- System status indicators
- Processing visualizations
- AI presence markers
- Background patterns (subtle)

### SVG Files
- `motifs/holographic-intelligence-core.svg` – Main motif
- `motifs/holographic-intelligence-rings.svg` – Signal rings only
- `motifs/holographic-intelligence-neural.svg` – Neural web
- `motifs/holographic-intelligence-pulse.svg` – Animated pulse element

---

## 🏛️ Motif 3: Celestial Throne / Cosmic Sanctuary

### Concept
Monumental symmetrical architecture representing **sovereign command, cosmic order, and sanctuary**. The throne is the central focal point of the Omega-9 ecosystem.

### Visual Specifications
- **Architecture**: Symmetrical, monumental, precise
- **Details**: Antique gold (#D4AF37) filigree and borders
- **Atmosphere**: Deep teal (#0F172A to #1E3A8A gradient)
- **Focal Point**: Central throne or command chair
- **Light**: Dramatic but controlled volumetric light

### Components
1. **Throne Structure**: Symmetrical chair with gold details
2. **Arch**: Monumental archway behind throne
3. **Steps**: 3-5 steps leading to throne
4. **Columns**: Fluted columns with gold capitals
5. **Nebula Background**: Subtle cosmic gradient (cinematic only)

### Usage
- Hero backgrounds
- Command center visualizations
- Sovereign authority representations
- Cinematic environments

### SVG Files
- `motifs/celestial-throne-full.svg` – Complete scene
- `motifs/celestial-throne-simple.svg` – Minimal version
- `motifs/celestial-arch.svg` – Arch element only
- `motifs/celestial-columns.svg` – Column pair

---

## ✅ Status Indicator System

### Design Principles
- **Symbol + Color + Label** for accessibility
- **Consistent sizing**: 24px, 32px, 48px variants
- **Clear hierarchy**: Status > Symbol > Color

### Icons (SVG)

#### 1. Verified
```
Symbol: Circle with checkmark
Color: Cyan (#00D4FF)
Stroke: 2px
Fill: Transparent background, solid symbol
```
Files:
- `icons/status-verified-24.svg`
- `icons/status-verified-32.svg`
- `icons/status-verified-48.svg`

#### 2. Reported
```
Symbol: Triangle (point up)
Color: Violet (#6366F1)
Stroke: 2px
Fill: Transparent background, solid symbol
```
Files:
- `icons/status-reported-24.svg`
- `icons/status-reported-32.svg`
- `icons/status-reported-48.svg`

#### 3. Pending
```
Symbol: Hourglass
Color: Gold (#D4AF37)
Stroke: 2px
Fill: Transparent background, solid symbol
```
Files:
- `icons/status-pending-24.svg`
- `icons/status-pending-32.svg`
- `icons/status-pending-48.svg`

#### 4. Blocked
```
Symbol: Square with slash or filled square
Color: Red (#EF4444)
Stroke: 2px
Fill: Solid for emphasis
```
Files:
- `icons/status-blocked-24.svg`
- `icons/status-blocked-32.svg`
- `icons/status-blocked-48.svg`

#### 5. Failed
```
Symbol: Circle with X
Color: Deep red (#7C2D12)
Stroke: 2px
Fill: Transparent background, solid symbol
```
Files:
- `icons/status-failed-24.svg`
- `icons/status-failed-32.svg`
- `icons/status-failed-48.svg`

---

## 📊 Governance Diagram System

### Diagram Types

#### 1. Command Hierarchy
**Visual Language:**
- Tree structure with thin cyan connectors
- Nodes with status indicators
- Gold borders for authority levels
- Clear parent-child relationships

**Components:**
- Node: Rounded rectangle, variable size by importance
- Connector: 1px cyan line, arrowheads for direction
- Label: Positioned below or beside node

**Example Structure:**
```
Sovereign (Gold border, Cyan glow)
    ├── Command (Standard node)
    │   ├── Sub-command (Smaller node)
    │   └── Sub-command
    └── Command
        └── Sub-command
```

#### 2. Identity & Role Boundaries
**Visual Language:**
- Concentric circles or nested rectangles
- Color-coded by role type
- Thin cyan boundary lines
- Status indicators on each boundary

**Components:**
- Boundary: 1px cyan stroke, rounded corners
- Entity: Icon + label inside boundary
- Connection: Dashed cyan line for relationships

#### 3. Security Scanning
**Visual Language:**
- Radial scan lines from center
- Progress arcs
- Status indicators at scan points
- Holographic intelligence motif overlay

**Components:**
- Scan origin: Holographic core
- Scan lines: Thin cyan, rotating or pulsing
- Target: Entity being scanned
- Results: Status indicators at intersection points

#### 4. Evidence Provenance
**Visual Language:**
- Flowchart with directional connectors
- Document icons with status
- Timestamp labels
- Verification badges

**Components:**
- Evidence node: Rectangle with document icon
- Verification: Cyan checkmark overlay
- Chain: Connecting lines showing provenance path
- Metadata: Small labels for timestamps, sources

#### 5. Risk Gates
**Visual Language:**
- Gate/barrier symbols
- Traffic light style indicators
- Flow paths through gates
- Blocked paths clearly marked

**Components:**
- Gate: Vertical bars or archway symbol
- Path: Line showing flow direction
- Indicator: Status symbol at gate
- Label: Risk level and description

#### 6. Policy Freezing
**Visual Language:**
- Ice/snowflake motifs
- Lock symbols
- Frozen state indicators
- Blue-tinted elements

**Components:**
- Policy document: Rectangle with lock icon
- Freeze indicator: Snowflake or ice crystal
- Status: Pending or Verified state
- Duration: Time indicator

#### 7. Audit History
**Visual Language:**
- Timeline with vertical markers
- Event cards with status
- Connecting lines
- Filter controls

**Components:**
- Timeline: Horizontal line with date markers
- Event: Card with icon, title, timestamp, status
- Connector: Vertical line from timeline to event
- Filter: Dropdown or tag selection

#### 8. Release Status
**Visual Language:**
- Progress bars or rings
- Version tags
- Status indicators
- Dependency trees

**Components:**
- Release: Circle or rectangle with version
- Status: Positioned indicator
- Progress: Radial or linear progress bar
- Dependency: Connecting lines to related releases

---

## 🖥️ UI Components

### Panels & Containers

#### 1. Primary Panel
```
Background: Midnight Navy (#0F172A)
Border: 1px Antique Gold (#D4AF37) or 1px Cyan (#00D4FF)
Radius: 4px or 8px
Padding: 24px
Shadow: Subtle, 0 4px 16px rgba(0, 212, 255, 0.1)
```

#### 2. Secondary Panel
```
Background: Obsidian Black (#0A0A0F)
Border: 1px Sapphire (#1E3A8A) at 50% opacity
Radius: 4px
Padding: 16px
```

#### 3. Card
```
Background: Midnight Navy (#0F172A)
Border: None or 1px Cyan at 20% opacity
Radius: 8px
Padding: 16px
Hover: Border becomes 100% opacity Cyan
```

### Buttons

#### Primary Button
```
Background: Electric Cyan (#00D4FF)
Text: Obsidian Black (#0A0A0F)
Border: None
Radius: 4px
Padding: 12px 24px
Hover: Background lightens to #33DDFF
Active: Background darkens to #00AACC
```

#### Secondary Button
```
Background: Transparent
Text: Electric Cyan (#00D4FF)
Border: 1px Cyan
Radius: 4px
Padding: 12px 24px
Hover: Background rgba(0, 212, 255, 0.1)
Active: Background rgba(0, 212, 255, 0.2)
```

#### Gold Button (High Importance)
```
Background: Antique Gold (#D4AF37)
Text: Obsidian Black (#0A0A0F)
Border: None
Radius: 4px
Padding: 12px 24px
Hover: Background lightens to #E6C249
Active: Background darkens to #B8860B
```

### Form Elements

#### Input Field
```
Background: Obsidian Black (#0A0A0F)
Border: 1px Sapphire (#1E3A8A) at 50% opacity
Radius: 4px
Padding: 12px 16px
Text: Ice White (#F8F9FA)
Placeholder: Ice White at 50% opacity
Focus: Border becomes Cyan (#00D4FF) at 100% opacity
```

#### Select Dropdown
```
Background: Obsidian Black (#0A0A0F)
Border: 1px Sapphire at 50% opacity
Radius: 4px
Padding: 12px 16px
Text: Ice White
Arrow: Cyan chevron
Focus: Border becomes Cyan
Hover: Background rgba(0, 212, 255, 0.05)
```

#### Checkbox/Radio
```
Unchecked: 2px Cyan border, transparent fill
Checked: 2px Cyan border, solid Cyan fill
Size: 20px
Label spacing: 8px
```

### Navigation

#### Sidebar
```
Width: 256px
Background: Obsidian Black (#0A0A0F)
Border: 1px Cyan at 10% opacity (right side)
Padding: 24px
```

#### Navigation Item
```
Padding: 12px 16px
Text: Ice White at 70% opacity
Icon: 20px, Ice White at 70% opacity
Hover: Text and icon at 100% opacity
Active: Background rgba(0, 212, 255, 0.1), text at 100%
Selected: Background rgba(0, 212, 255, 0.15), Cyan left border 3px
```

---

## 🎨 Background Patterns

### 1. Subtle Grid
```
Color: Cyan at 5% opacity
Size: 4px lines, 64px spacing
Usage: Panel backgrounds, subtle texture
```

### 2. Holographic Mesh
```
Color: Cyan at 10% opacity
Pattern: Hexagonal grid with thin lines
Size: 32px hexagons
Usage: Technical surfaces, data visualizations
```

### 3. Lion Silhouette Watermark
```
Color: White at 5% opacity
Size: Variable, tiled or single
Usage: Backgrounds requiring authority presence
```

### 4. Celestial Gradient
```
Colors: Midnight Navy to Deep Sapphire
Direction: Diagonal or radial
Usage: Hero sections, cinematic backgrounds
```

---

## 📱 Responsive Guidelines

### Breakpoints
```
Mobile: < 768px
Tablet: 768px - 1024px
Desktop: 1024px - 1440px
Wide: > 1440px
```

### Adaptations
- **Motifs**: Simplified versions for mobile, full for desktop
- **Spacing**: Reduced on mobile (scale by 0.75)
- **Typography**: Scale down by 1-2 levels on mobile
- **Navigation**: Collapse sidebar to hamburger menu
- **Panels**: Stack vertically on mobile

---

## 🚫 Prohibited Elements

### Do NOT Use
- ❌ Generic cyberpunk clutter
- ❌ Random glyphs or fake text
- ❌ Excessive neon effects
- ❌ Decorative effects that obscure information
- ❌ Color-only status indicators
- ❌ Illustrative metrics presented as verified facts
- ❌ Secrets, credentials, or sensitive financial information in imagery
- ❌ Overly complex gradients or patterns
- ❌ Inconsistent motif representations

---

## 📁 File Structure

```
design-system/
├── FISK_DIMENSION_DESIGN_SYSTEM.md    # This document
├── palette/
│   ├── palette.json                     # Color definitions
│   ├── palette.css                      # CSS variables
│   └── palette.sass                     # SASS variables
├── motifs/
│   ├── regal-sentinel-full.svg
│   ├── regal-sentinel-profile.svg
│   ├── regal-sentinel-head.svg
│   ├── regal-sentinel-silhouette.svg
│   ├── holographic-intelligence-core.svg
│   ├── holographic-intelligence-rings.svg
│   ├── holographic-intelligence-neural.svg
│   ├── holographic-intelligence-pulse.svg
│   ├── celestial-throne-full.svg
│   ├── celestial-throne-simple.svg
│   ├── celestial-arch.svg
│   └── celestial-columns.svg
├── icons/
│   ├── status-verified-24.svg
│   ├── status-verified-32.svg
│   ├── status-verified-48.svg
│   ├── status-reported-24.svg
│   ├── status-reported-32.svg
│   ├── status-reported-48.svg
│   ├── status-pending-24.svg
│   ├── status-pending-32.svg
│   ├── status-pending-48.svg
│   ├── status-blocked-24.svg
│   ├── status-blocked-32.svg
│   ├── status-blocked-48.svg
│   ├── status-failed-24.svg
│   ├── status-failed-32.svg
│   └── status-failed-48.svg
├── ui/
│   ├── buttons.css
│   ├── panels.css
│   ├── forms.css
│   └── navigation.css
├── diagrams/
│   ├── hierarchy-template.svg
│   ├── boundaries-template.svg
│   ├── scanning-template.svg
│   ├── provenance-template.svg
│   ├── risk-gates-template.svg
│   ├── policy-freeze-template.svg
│   ├── audit-history-template.svg
│   └── release-status-template.svg
├── assets/
│   ├── background-patterns/
│   ├── textures/
│   └── examples/
└── examples/
    ├── dashboard-layout.html
    ├── dashboard-layout.css
    ├── presentation-template.html
    ├── presentation-template.css
    └── governance-diagram-example.svg
```

---

## 🎯 Implementation Checklist

- [ ] Color palette defined and tested
- [ ] All three motifs created in SVG
- [ ] Status icons created in multiple sizes
- [ ] UI components styled consistently
- [ ] Diagram templates created
- [ ] Responsive adaptations verified
- [ ] Accessibility contrast checked
- [ ] All prohibited elements avoided
- [ ] Consistent motif usage across examples

---

## 📝 Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0.0 | 2024-XX-XX | Initial canonical visual system |

---

## 👑 Sovereign Authority

This design system is the **canonical visual identity** for Fisk Dimension and Omega-9. All implementations must adhere to these specifications to maintain system integrity and command hierarchy.

**KING NEXUS oversees all.**
