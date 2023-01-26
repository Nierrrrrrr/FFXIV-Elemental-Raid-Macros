---
layout: default
title: 3. Brute Justice + Cruise Chaser
parent: Lv 80. TEA
grand_parent: Ultimates
permalink: /ultimates/tea/zh-tw/03_bjcc/
---

# 殘暴正義號 + 巡航驅逐者

這個階段我偏好的打法是 [我的 Tollgate 打法](https://na.finalfantasyxiv.com/lodestone/character/10898230/blog/4941271/)，非常類似於 MOOF 的打法，將兩隻王重疊拉在場地正中間。

「Tollgate」名字的由來在於第三次傳毒的時候，坦補會排成一直線來傳毒。有人曾經說這種傳毒的過程就像是在穿越剪票口感覺，以此靈感命名。

這個打法簡化了水/雷和傳毒的過程，**取而代之的代價就是會增加坦克受到的傷害**，這個階段是整場戰鬥中治療壓力偏高的階段，請做好準備。

坦克們盡量在每次傳雷的時候都要使用小的減傷來降低受到的傷害。

<table>
  <tr>
    <td>大致上來看整個階段的移動，坦克會將兩隻王拉在場地正中間，而補師會有一些些許的移動。<br><br>DPS 需要相較之下較大量的移動，大致的移動路徑和時間點如圖所示。</td>
	<td><img src="../images/bjcc/bjcc_overview.jpg"></td>
  </tr>
</table>

<div style="background-color: #002 ; padding: 10px; border: 1px solid;">
<details markdown=block>
<summary><b>[點擊展開] 水/雷和最終判決（毒）的詳細說明</b></summary>
<p>這個階段有兩個「燙手山芋」由全隊同時不停傳遞。</p>
<p><b>循環 1: 水/雷:</b></p>
<p>水雷是 2 個 30 秒的 debuff，當狂暴正義號詠唱「系統連接」的時候施放於 2 個玩家身上。</p><p>當倒數計時結束，debuff 會以玩家為中心造成一個可以分攤的 AOE 傷害。</p>
<ul>
  <li>如果帶有 debuff 的玩家死亡，debuff 會直接爆炸並滅團。</li>
  <li>Debuff 爆炸之後，debuff 會隨機傳遞給受到 debuff 傷害的其他玩家其中一位。</li>
  <li>如果 debuff 沒有擊中其他玩家 (例如: 單吃 debuff)，會直接產生全地圖爆炸傷害並滅團。</li>
  <li>原本擁有 debuff 的玩家在爆炸後會獲得一個對應屬性的耐性降低的 debuff，所以他們<em>不能</em> 連續參與同一個屬性的兩次分傷。</li>
</ul>
<table>
  <tr>
    <td><img src="../images/bjcc/debuffs/compressed_water.png"></td>
    <td><p><b>水屬性壓縮</b></p><ul><li>從 1 位<b>隨機補師</b>開始。</li><li>越多玩家被擊中，則單一玩家受到的傷害越少。</li><li>至少三位玩家要一起分攤水屬性壓縮。</li><li>在原本擁有 debuff 的玩家腳下會長出一個水柱。<ul><li>玩家太靠近長出來的水柱則會被秒殺。</li><li>水柱必須被狂暴正義號的冰圈冰凍，或是狂暴正義號的噴火蒸發，如果處理失敗的話則會滅團。</li></ul></li></ul></td>
  </tr>
  <tr>
    <td><img src="../images/bjcc/debuffs/compressed_lightning.png"></td>
    <td><p><b>雷屬性壓縮</b></p><ul><li>從 1 位<b>隨機 DPS</b>開始。</li><li>越多玩家被擊中，則單一玩家受到的傷害<b>越高</b>。</li><li>因此，我們希望每次雷屬性壓縮的時候必須是<b>剛好兩位玩家</b>參與 <em>（一位是帶著雷屬性壓縮的玩家，另一位則是我們希望將雷屬性壓縮傳遞過去的玩家）</em>。</li></ul></td>
  </tr>
</table>
<p><b>循環 2: 最終判決:</b></p>
<p>這些是當狂暴正義號詠唱「非最終審判」時會給全體 DPS 或是全體坦補施放的持續傷害 debuff。（譯註: 通常我們簡稱為毒）</p>
<table>
  <tr>
    <td>
      <img src="../images/bjcc/debuffs/final_decree_nisi_alpha.png">
      <img src="../images/bjcc/debuffs/final_decree_nisi_beta.png">
      <img src="../images/bjcc/debuffs/final_decree_nisi_gamma.png">
      <img src="../images/bjcc/debuffs/final_decree_nisi_delta.png">
    </td>
    <td><p><b>最終判決（後面簡稱為毒） αβγδ</b></p>
      <ul>
        <li>當有毒的玩家碰觸到一個沒有毒的玩家，被碰觸的玩家會獲得一個相同且時間重新計時的毒。</li>
        <li>如果兩個擁有<b>不同毒</b>的玩家彼此觸碰到則會直接死亡</li>
      </ul>
    </td>
  </tr>
</table>
<p>戰鬥途中，狂暴正義號會詠唱「終審開庭」，會給所有玩家「解藥」，這個機制會在狂暴正義號詠唱「終審閉庭」時做檢查。</p><p>當「終審開庭」詠唱完畢時，會將下列的 debuff 施放於所有玩家:</p>
<table>
  <tr>
    <td>
      <img src="../images/bjcc/debuffs/final_judgment_decree_nisi_alpha.png">
      <img src="../images/bjcc/debuffs/final_judgment_decree_nisi_beta.png">
      <img src="../images/bjcc/debuffs/final_judgment_decree_nisi_gamma.png">
      <img src="../images/bjcc/debuffs/final_judgment_decree_nisi_delta.png">
    </td>
    <td><p><b>終審判決（後面簡稱為解藥） αβγδ</b></p>
      <ul>
        <li>每種類型的解藥會施放於 2 個玩家身上 - 1 個坦/補，和 1 個 DPS。</li>
        <li>每位玩家在「終審閉庭」施放完畢的時候<b>必須擁有和解藥對應的毒</b>，否則就會團滅。</li>
      </ul>
    </td>
  </tr>
</table>
<p>隊伍必須維持這兩種毒的持續傳遞，傳遞水、雷和所有類型的毒 debuff 一直到狂暴正義號施放「終審閉庭」為止，詠唱結束後會清除所有玩家身上的所有 debuff。</p>
</details>
</div>

## 走位

<table>
  <tr>
    <td><p><b>1.</b> 初始站位</p><p><ul><li><b>MT</b>: 坦巡航驅逐者</li><li><b>ST</b>: 坦狂暴正義號</li></ul></p><p><em>（注意 MT 和 ST 的初始站位和一般常見的站位是相反的，坦克們要坦的王會生在他們初始站位的那一側）</em></p></td>
	<td><img src="../images/bjcc/bjcc_01.jpg"></td>
  </tr>
  <tr>
    <td><p><b>2.</b> 兩個齒輪出現在八方位的其中兩個位置且一定互相是在對面，剛好會將隊伍拆成兩組。</p><p>所以玩家移動到場地邊緣躲避齒輪並且誘導「鷹式破壞炮」。</p></td>
	<td><img src="../images/bjcc/bjcc_02.jpg"></td>
  </tr>
  <tr>
    <td><p><b>3.</b> 當齒輪判定後，巡航驅逐者會詠唱「制導」，在所有玩家腳下施放大型可誘導的圓形 AoE。</p><p>所有玩家往場中心移動。</p><p>坦克位置互相交換。</p><p><ul><li><b>ST</b>: 先走進場地中心的小圈圈，並等待<b>MT</b>經過</li></ul></p></td>
	<td><img src="../images/bjcc/bjcc_03.jpg"></td>
  </tr>
  <tr>
    <td><p><b>4.</b> 巡航驅逐者會停止移動並詠唱「光子炮」。</p><p><b>這是一個盾值檢測</b>，當光子炮會將所有玩家的 HP 歸 1，如果沒有盾的話，毒的 DoT 會殺死帶毒的四位玩家。</p><ul><li><b>MT:</b> 穿越場中到西側。<em>（巡航驅逐者不會跟著移動，不過等待的時候你可以打幾個 GCD 在狂暴正義號身上）</em></li></ul></td>
	<td><img src="../images/bjcc/bjcc_04.jpg"></td>
  </tr>
  <tr>
    <td><p><b>5.</b> 兩個坦克可以趁這時盡量將王拉到場地正中心。<em>（可以利用王目標圈兩側的箭頭來幫助定位）</em></p><p>兩隻王不用<em>完全</em>南北置中，但要盡可能地做到東西置中。</p><p>光子炮之後就是<b>第一次傳毒</b>。</p><p><ul><li><b>MT</b>, <b>D1</b>: 先不要傳毒。</li><li><b>ST</b>, <b>D2</b>: 互相傳毒。</li><li><b>H1</b>, <b>D3</b>: 互相傳毒。</li><li><b>H2</b>, <b>D4</b>: 互相傳毒。</li></ul></p></td>
	<td><img src="../images/bjcc/bjcc_05.jpg"></td>
  </tr>
  <tr>
    <td><p><b>6.</b> 巡航驅逐者詠唱「迴旋碎踢」</p><p><ul><li><b>MT</b>: Dodge Spin Crusher and pass Nisi with <b>D1</b>.</li><li><b>H1</b>, <b>H2</b>: The healer <em>with</em> Water goes to the first Water position (<b>H1</b> in this example). The healer <em>without</em> Water can preposition to bait Fire and the Hidden Mine.</li><li><b>D1</b>: Note <b>D1</b> is <em>never</em> involved in the first Water stack.</li><li><b>D3</b>: Be careful if you have the first Thunder as your path may cross <b>D2</b>'s path to the Water stack.</li></ul></p></td>
	<td><img src="../images/bjcc/bjcc_06.jpg"></td>
  </tr>
  <tr>
    <td><p><b>7. First Water/Thunder pass</b>.</p><p><ul><li>Water: Healer + at least two of <b>D2</b>, <b>D3</b>, <b>D4</b> (excluding whoever had Thunder)</li><li>Thunder: DPS → <b>ST</b></li><li><b>D1</b>: You may need to avoid the Thunder explosion by moving towards the <b>MT</b>.</li></ul></p></td>
	<td><img src="../images/bjcc/bjcc_07.jpg"></td>
  </tr>
  <tr>
    <td><p><b>8.</b> After Water resolves, Healers and DPS move to prepare for Hidden Mines and Enumeration.</p><p><ul><li><b>D2</b>: Move under the bosses, between the two tanks.</li><li><b>D3</b>: Move behind the <b>MT</b></li><li><b>D4</b>: Move behind the <b>ST</b>.</li></ul></p><p>All DPS should stay within the sector marked by the green dotted line:<ul><li>This prevents the DPS baiting the Hidden Mines by accident.</li><li>This prevents the DPS from getting hit by the Hidden Mines when they explode later.</li></ul></p></td>
	<td><img src="../images/bjcc/bjcc_08.jpg"></td>
  </tr>
  <tr><td>
    <p><b>9.</b> This is the most involved step for everybody in this phase.</p>
    <p><b>Tanks:</b> One tank (at random) will be chosen to resolve Ice.</p>
    <p>
      <ul>
        <li>If a player gets too close to the water tornado, the tornado will tether to the player, knocking them back and dealing very high damage (one-shotting them).</li>
        <li>The Ice puddle should be dropped so that it <b>just misses the Water tornado</b> <em>(see image)</em>. The Ice puddle will then expand once and freeze the tornado.</li>
      </ul>
    </p>
    <p>
      <b>Healers:</b> Bait Fire puddles and Hidden Mines before joining the Enumeration groups.
    </p>
    <p>
      <ul>
        <li><b>H1</b>: Always west Enumeration.</li>
        <li><b>H2</b>: Always east Enumeration.</li>
      </ul>
    </p>
    <p><b>DPS:</b> Resolve Enumeration with the Healers.</p>
    <p>If either side has both Enumerations (or equivalently, no Enumerations), <b>D1</b> and <b>D2</b> swap sides.</p>
    <p>
      <ul>
        <li><b>D1</b>: West Enumeration unless a swap is needed.</li>
        <li><b>D2</b>: East Enumeration unless a swap is needed.</li>
        <li><b>D3</b>: Always west Enumeration.</li>
        <li><b>D4</b>: Always east Enumeration.</li>
      </ul>
    </p>
    <p>All non-tanks should stay inside the sector marked by the green dotted line <em>(note it has expanded since the Hidden Mines have been baited)</em>.</p>
  </td>
	<td><img src="../images/bjcc/bjcc_09.jpg"><img src="../images/bjcc/bjcc_ice.jpg"></td>
  </tr>
  <tr>
    <td><p><b>10.</b> After resolving Ice (if applicable), tanks wait for the Hidden Mine to drop first, before taking the Hidden Mine on their side. This is a heavy AoE tankbuster.</p><p>Healers and DPS should stay inside the sector marked by the green dotted line to avoid getting clipped by the Hidden Mine's AoE.</p></td>
	<td><img src="../images/bjcc/bjcc_10.jpg"></td>
  </tr>
  <tr>
    <td><p><b>11. Second Nisi pass.</b></p><p>Melee + Tanks be careful as the Ice will expand.<ul><li><b>MT</b>, <b>ST</b>: Pass Nisi with the nearest melee on your side (they may have swapped sides)</li><li><b>D1</b>, <b>D2</b>: Pass Nisi with the nearest tank on your side (you may have swapped sides)</li><li><b>H1</b>, <b>D3</b>: Pass Nisi with each other.</li><li><b>H2</b>, <b>D4</b>: Pass Nisi with each other.</li></ul></p></td>
	<td><img src="../images/bjcc/bjcc_11.jpg"></td>
  </tr>
  <tr>
    <td><p><b>12. Second Water + Lightning pass.</b></p><p><ul><li><b>Water:</b> All DPS</li><li><b>Thunder:</b> ST → MT</li></ul></p><p><ul><li><b>MT</b>: Face Cruise Chaser west after receiving Thunder.</li></ul></p><p>Keep in mind that Cruise Chaser will autoattack the MT after this Lightning pass.</p></td>
	<td><img src="../images/bjcc/bjcc_12.jpg"></td>
  </tr>
  <tr>
    <td><p><b>13.</b> Plasma Shield spawns. Tanks and Healers line up to form the Tollgate.</p><p><ul><li><b>ST:</b> Point Brute Justice south to hit the waterspout with Flarethrower.</li></ul></p></td>
	<td><img src="../images/bjcc/bjcc_13.jpg"></td>
  </tr>
  <tr>
    <td><p><b>14. Third Nisi pass</b>.</p><p>After the Plasma Shield is destroyed, the DPS pass through this "tollgate" to pass Nisi with the appropriate tank/healer before gathering in the south-east corner for the third Water pass.</p><p><ul><li>The DPS that was the second Water passes Nisi to their partner, but does <b>not</b> cross the tollgate, returning west instead.</li></ul></p></td>
	<td><img src="../images/bjcc/bjcc_14.jpg"></td>
  </tr>
  <tr>
    <td><p><b>15. Third Water + Lightning pass</b>.</p><p><ul><li>Water: All DPS (except 2nd Water) + H2</li><li>Thunder: MT → H1</li></ul></p></td>
	<td><img src="../images/bjcc/bjcc_15.jpg"></td>
  </tr>
  <tr>
    <td><p><b>16. Fourth Nisi pass</b>.</p><p>Tank and healer positions are fixed (<b>MT > H1 > ST > H2</b>). DPS pass with the appropriate tank or healer.</p><p><ul><li><b>MT</b>: Pull Cruise Chaser to the east of the Ice block.</li></ul></p></td>
	<td><img src="../images/bjcc/bjcc_16.jpg"></td>
  </tr>
  <tr>
    <td><p><b>17.</b> Cruise Chaser casts Propeller Wind.</p><p>Players must use the frozen Ice to block line-of-sight to Cruise Chaser, or they will become confused and run around uncontrollably.</p><p><ul><li><b>MT</b>: Join the Nisi lineup.</li></ul></p></td>
	<td><img src="../images/bjcc/bjcc_17.jpg"></td>
  </tr>
  <tr>
    <td><p><b>18.</b> Cruise Chaser casts Photon, bringing both tanks down to 1HP.</p><p>Brute Justice then prepares Double Rocket Punch, a two-man shared tankbuster.</p><p><ul><li><b>D3</b>: Bait Brute Justice's Super Jump south.</li></ul></p></td>
	<td><img src="../images/bjcc/bjcc_18.jpg"></td>
  </tr>
  <tr>
    <td><p><b>19.</b> Brute Justice targets the furthest player and casts Apocalyptic Ray.</p><p>After this, Cruise Chaser casts two Whirlwinds (one after the other) before both bosses start casting their enrage. If one boss dies, the other starts casting their enrage.</p></td>
	<td><img src="../images/bjcc/bjcc_19.jpg"></td>
  </tr>
</table>

## Frequently Asked Questions

<details markdown=block>
<summary><b>[Tank swap]</b> Why don't we do a Provoke swap instead of having the two tanks cross each other (especially with Nisi)?</summary>
<table>
  <tr><td><p>Two reasons:<ol><li>If a tank happens to die in Limit Cut and gets raised at the start of BJCC, their first instinct is to Provoke whichever boss they're supposed to hold. Now that Provoke has been used, you cannot then swap the bosses by Provoking the other right after Chakrams go off.</li><li>Cruise Chaser stops to cast Photon. If you swap bosses using Provoke, the tank that Provoked Cruise Chaser can only attack Brute Justice, and either has to hold damage, potentially steal hate back, or resort to stance dancing tricks that is more trouble than it is worth.</li></ol></p></td></tr>
</table>
</details>
<details markdown=block>
<summary><b>[Crashing Thunder]</b> Why did this deal more damage than usual?</summary>
<table>
  <tr><td><p>Water and Thunder work differently.</p><p>While Crashing Wave works like any other stack damage (damage is lowered as more people are hit by Crashing Wave), Thunder is the opposite; damage <em>increases</em> as more people are hit by Crashing Thunder.</p><p>This is why we want the Thunder stacks to contain exactly two players.</p></td></tr>
</table>
</details>
<details markdown=block>
<summary><b>[Hidden Mines]</b> Why doesn't D3 bait the west Hidden Mine instead of H1?</summary>
<table>
  <tr><td><p>The objective is to have both Enumeration targets visible and in close proximity to one another.</p><p>Suppose D3 and H2 baited the Hidden Mines instead and D2 and D3 were targeted for Enumeration.</p><p>D2 only sees the Enumeration on D2, but now has to look at D3 to determine whether they need to switch positions with D1, with two giant robots in the center blocking the view.</p></td></tr>
</table>
</details>
<details markdown=block>
<summary><b>[Hidden Mines]</b> Why don't we bait the Hidden Mines towards the outer edge of the arena? Doesn't that put the healers further away from Brute Justice so a ranged DPS doesn't bait a Hidden Mine by mistake?</summary>
<table>
  <tr><td><p>The idea is to keep both bosses in the center. In particular, if the West mine is baited towards the edge, the MT has to pull Cruise Chaser closer to the edge in order to take the Hidden Mine, and doesn't leave much space for the DPS to fit in for the Plasma Shield.</p><p>Of course, you could have the MT and ST switch sides again to recenter the bosses, but that violates a different principle which is to try and keep the tanks and healers to their half of the arena as much as possible.</p></td></tr>
</table>
</details>
<details markdown=block>
<summary><b>[Hidden Mines]</b> What went wrong with the Hidden Mine baits? Why was a mine baited on the DPS instead of a healer?</summary>
<table>
  <tr><td><p>The Hidden Mines are baited by the two furthest players from Brute Justice, which should be the healers.</p><p>If a DPS ended up baiting the Hidden Mine, it is likely because:<ul><li>A DPS was outside the green sector marked in Step 7 above <em>or</em></li><li>The ST did not position Brute Justice in the center of the arena.</li></ul></p></td></tr>
</table>
</details>