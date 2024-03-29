# github_action_pebble_build

GitHub Action that builds Pebble Apps and Watchfaces

https://github.com/marketplace/actions/pebblebuild

Source available from https://github.com/clach04/github_action_pebble_build

Uses the Rebble/Pebble SDK version 4.5.

Currently works if copy/pasted into project. NOTE remove marked lines https://github.com/clach04/github_action_pebble_build/blob/main/action.yml#L6

:exclamation: Does NOT work as a Market Place import :exclamation: See https://github.com/clach04/github_action_pebble_build/issues/1

To see this in action see https://github.com/clach04/pebble_watchface_framework

NOTE Downloads are ONLY available when logged into Github, otherwise, the Artifacts "PebblePBW" text is not a link (without any hint as to what is going on).

## Thanks

Thanks and kudos to:

  * https://github.com/daktak - the original creator of Pebble GitHub Actions
      * First seen in [mattrossman/forecaswatch2#50](https://github.com/mattrossman/forecaswatch2/pull/50)
  * Everyone on the Rebble team for keeping Pebbles usable
  * All the cool people with useful/viable/workable solutions and advice to:
      * https://github.com/actions/setup-python/issues/672
      * https://github.com/actions/runner-images/issues/7401
  * https://github.com/coatl-dev/docker-six - which I have not used but like having in my back pocket
  * https://github.com/MatteoH2O1999/setup-python - which I have not used but like having in my back pocket
