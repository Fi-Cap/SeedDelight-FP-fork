# [SeedDelight-FP-fork]
 
A forked version of [SeedDelight](github.com/HiedaCamellia/SeedDelight)(Original Mod URL) to fix item drop functionality and refine underlying code structure.
 
## About This Fork
 
This fork addresses a key issue in the original mod: the item drop probability system was non-functional due to disorganized logic. The primary work focuses on restructuring the item handling code to:
 
1. Get predictable, working probability-based item drops (the core fix)
2. Clean up tangled, hard-to-maintain code related to item spawning
3. Preserve all other original gameplay features (no new mechanics added—just fixing and refining)
 
I’ll sync this fork with the original repository’s updates when possible. If the fixed drop logic and cleaned code align with the original mod’s vision, I may submit a Pull Request to share the improvements back.
 
## Key Fixes & Refactors
 
- Restructured the item drop calculation module to resolve broken probability logic—items now drop at the intended rates
- Simplified redundant code in the item spawning system (removed duplicate checks that caused inconsistencies)
- Added basic comments to the drop logic for easier future troubleshooting (no changes to how the mod plays, just clarity for maintenance)
 
## Acknowledgments
 
Big thanks to the [HiedaCamellia](https://github.com/HiedaCamellia) for creating the original mod—this fork only exists to fix a critical functionality gap in their work. If you like this mod, support the original project first!
 
Notes
 
- This fork is for [GNU LESSER GENERAL PUBLIC LICENSE(GLGPL)]—check the original mod’s license before sharing further
- Report issues specific to the fixed drop logic in this fork’s Issues tab. You can also report issues related to the original mod that have not yet been addressed by its contributors here.
