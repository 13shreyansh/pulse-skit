# Phase 5: Testing Notes

## All Scenes Verified Working:
- Scene 1 (Marina Bay): ✅ Ken Burns zoom in
- Scene 2 (Cyclist): ✅ Pan right animation
- Scene 3 (Fall): ✅ Shake effect
- Scene 4 (Google Doctor): ✅ Zoom in
- Scene 4b (Phone Screen): ✅ Phone overlay on black
- Scene 5 (Overconfident Helper): ✅ "Trust the process bro" text overlay
- Scene 7 (Panicker): ✅ Vibrate + "MA, SOMEONE IS DYING" shaky text
- Scene 8 (Carrying): ✅ Pan right
- Scene 9 (Hospital 1): ✅ Red "Full." text
- Scene 10 (Hospital 2): ✅ Red "No trauma center." text (needs testing)
- Scene 11 (Hospital 3): ✅ Sign overlay + desaturation
- Scene 12 (Defeat): ✅ Full desaturation, dark mood
- Scene 13 (Statistics): ✅ Sequential text on black, advances with arrow
- Scene 14 (Bridge): ✅ "What if one tap..." italic text

## Issues to Fix:
1. Instructions overlay stays visible after first scene starts - need to ensure it hides properly
2. Need to verify the instructions hide on first keypress (it should based on code)
3. The jumpToScene function maps keys 1-9 to indices 0-8, which is slightly off from scene IDs due to Scene 4b
