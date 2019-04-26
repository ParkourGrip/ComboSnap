# Combo Snap
 - **Unreal Tournament 4 mutator**
 - **blueprint name:** MutComboSnap
 - **version:** 0.0.0
 - **compatibility:** ++UT+Release-Next-CL-3525360

## Download .pak file
*insert download link here later*

## What does it do?
When applied, the mutator creates more consistent combo explosion behavior.
It does this by snapping the combo explosion location to a line grid placed on the shock ball travel path.

## Compatibility with other mutators
This mutator uses a custom implementation of the ShockBall class.
When applied, this mutator will change the secondary fire mode projectile class of every shock rifle to mutator's custom class.
The custom class is the stock shock ball with added grid snapping functionality.
So this mutator works well with stock weapons.
If you attempt to use this mutator with a custom shock rifle the primary fire mode of that custom shock rifle will stay unmodified but the secondary fire shock ball projectile will revert to the stock weapon values.

## How to open the source in the editor?

Clone the git repository or copy the files to:
`UnrealTournamentEditor\UnrealTournament\Content\ComboSnap`

