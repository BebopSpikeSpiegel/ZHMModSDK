# Evidence for OrfeasZ/ZHMModSDK#280 fix

Screenshots captured with an automated (MaaMCP) repro on HITMAN 3 3.290.1.0:
open the SDK overlay -> MODS -> untick a bundled UI mod (Noclip) -> OK.

1-3: official ZHMModSDK v4.2.1 (crash -> Streamline filter loop -> stack overflow)
4-6: branch `fix/imgui-context-hooks-on-mod-unload` (CI build) - mod unloads cleanly
