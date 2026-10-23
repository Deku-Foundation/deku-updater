# Deku Updater

Client-side update planning and activation for Deku Linux.

## Status

Future component. No supported system, authenticated package repository, or safe update transaction exists yet.

## Responsibilities when activated

- Verify repository metadata and package artifacts before installation.
- Coordinate staged updates with the package manager and system profile.
- Define failure recovery, rollback, reboot coordination and interrupted-update behavior.
- Provide understandable status and logs without hiding system changes.

## Dependencies and safety

Do not implement production update activation until deku-pkg supports authenticated metadata and recoverable transactions, and deku-signing's trust policy is reviewed. Prefer a tested upstream update mechanism for the initial technology-preview image.
