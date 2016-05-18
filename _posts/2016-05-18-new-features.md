---
layout: post
title: New Game Features
---

After two weeks of work, I have taken most of the feedback from the first demo and implemented them. The newest feature for the game is the introduction of monsters that the player must defeat, and the ability to defeat these monsters.

For those of you who are having issues playing the game, please first download and run the unity webplayer plugin **[here](https://unity3d.com/webplayer)**.

When the game starts, a random monster will begin attacking the player. The monster has 4 stats that the player can see and a health bar. The stats are described as follows; speed - the rate at which the monster attacks, strengh - the amount that the monster hits the player for, defense - the monster's ability to deflect sword attacks, and agility - the monster's ability to deflect gun attacks.

The player can defeat the monster through careful matching of correct tiles that will defeat the monster. Matching gun tiles will shoot, matching swords will slash, matching health will heal, and matching skulls will increase the player's defense against the next monster attack.

I would love your feedback on the numbers and your thoughts on if a monster is too difficult or too hard. Be aware that after defeating a monster, another of a higher level and stats will begin attacking.

Be sure to follow on facebook and twitter for more updates!

<div align="center">
  <object id="UnityObject"
      classid="clsid:444785F1-DE89-4295-863A-D46C3A781394"
      width="365"
      height="649"
      codebase="http://webplayer.unity3d.com/download_webplayer/UnityWebPlayer.cab#version=2,0,0,0">
    <param name="{{ site.baseurl }}/img/Match3game.unity3d"
      value="Match3game.unity3d" />
    <embed id="UnityEmbed"
      src="{{ site.baseurl }}/img/Match3game.unity3d"
      width="365"
      height="649"
      type="application/vnd.unity"
      pluginspage="http://www.unity3d.com/unity-web-player-2.x" />
  </object>
</div>