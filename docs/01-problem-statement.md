# Problem Statement

This document defines the problem BackTrackRTL is intended to address, summarizes existing approaches to the problem, and introduces the proposed solution.

## Problem

<!--
Describe the recovery problem without assuming BackTrackRTL is the solution.

Consider:
- Situations requiring autonomous recovery, such as loss of control/C2 link.
- Limitations of direct and altitude-based RTL in constrained environments.
- Operations without a preplanned mission path.
- Risks associated with returning through previously untraversed space.
- Scope of the problem and situations where it is relevant.
-->

## Existing and Related Solutions

<!--
Summarize existing approaches relevant to the problem.

Consider:
- PX4 RTL behavior and available strategies.
- Relevant PX4 failsafe/recovery behavior.
- ArduPilot SmartRTL.
- Breadcrumb/path-based recovery approaches.
- Strengths and limitations relevant to the problem being addressed.

Do not attempt to prove that BackTrackRTL is superior here.
-->

## Proposed Solution

<!--
Introduce BackTrackRTL at a high level.

Consider:
- Recording the vehicle's traversed path.
- Retracing that path during an applicable recovery event.
- Preference for faithful path retracing over shortest-path optimization.
- BackTrackRTL as an additional recovery strategy rather than a replacement
  for conventional RTL.
- What the project intends to implement and evaluate.

Detailed behavior belongs in requirements and design.
-->