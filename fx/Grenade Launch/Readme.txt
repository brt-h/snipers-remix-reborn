This is the first-pass blockout of the grenade launch.

Place the sniper_grenade_launch in your particles folder.
In the npc_abilities_custom,

"precache"
{
"particle_folder" "particles\sniper_grenade_launch"
}

The FireEffect to call is "sniper_grenade_launch.vpcf".

I will probably have to break these into multiple separate effects, in case the channel/spell is cancelled. Any questions or issues, email devogelt@gmail.com.