# ProjectileOffset

Adds an offset to a verb that can be configured via defmodextension

The verbclass needs to be replaced with:

    <verbClass>ProjectileOffset.Verb_LaunchWithOffset</verbClass>

The turret place worker with:

    <li>ProjectileOffset.PlaceWorker_ShowTurretRadiusWithOffset</li>

And the turret defmodextension (careful, not the turret gun's def, the turret def itself):  

    <modExtensions>
      <li Class="ProjectileOffset.ProjectileOffsetModExt">
        <offset>-7</offset>
      </li>
    </modExtensions>
