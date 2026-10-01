# Native diff geometry belongs to Resize

Heisenberg owns this native library fix with Toad integration PR271. Exact
upstream8f8aa2f source matches the installed0.1.5 Python package byte-for-byte.
No existing source owner/fork was present; this fork changes the original
DiffView definition, not a Toad override or a replacement renderer.

Actual original41MB PR269 video/profile includes DiffView.on_mount self.size
forcing Screen.find_widget/Compositor.full_map/full_arrange_root while restored
native body descendants are attaching. Native on_resize already consumes the
layout-owned event.size.width. Remove the premature Mount query; first layout
and subsequent Resize events own auto-split width. No stored width, readiness
flag, fallback, extra timer, family cases or status mirror. All NativeDiffView
subclasses inherit the same lifecycle, including Toad DiffView and PatchDiffView.

Actual Toad/Pilot source control with native library and private protocol:

* Original auto mode: wide65→narrow15→wide65 correctly splitsTrue/False/True.
* Candidate preserves that sequence; fixed unified mode staysFalse throughout.
* Native arrangements reached directly from DiffView.on_mount: baseline2,
  candidate0. Total arrangements17→15 in this control, not a CPU metric.
* No Agent/provider/public root; no application exception.

The control uses the existing native widgets, compositor, Resize delivery and
Toad application. Its instrumentation delegates original arrangement unchanged.
It is not installed original41MB acceptance and does not establish whole CPU,
firstpaint or resource readiness. Toad PatchDiffView and actual theme/visibility
consumer closure remain part of receiving271; no source-only READY claim.

Raw original video/phase/profile causal evidence stays protected under
/home/ts/.cache/agent-scratch/viewport-preparation-269-20261001-installed01/capture,
including causal-native-interior-stacks.json and causal-native-layout-handoff.md.
No extra physical capture has been launched for this change.
