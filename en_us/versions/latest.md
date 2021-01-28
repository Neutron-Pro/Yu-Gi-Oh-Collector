# Update 1.10.0
↪ *January 30, 2021*

**Special 1 year update !**

---

⇰ The database of Yu-Gi-Oh cards has been updated. 1,158 Yu-Gi-Oh cards have been introduced. (New cards and/or in different rarities)

# NEWS

⇰ **Commands**

• Prefixes on rarities and booster.
  *For more information do the command* `booster` or `rarities`.

⇰ **Filters**

• The `count` filter has been added to the `wikilist` command to retrieve all the cards you don't own.
  *Example :* `wikilist count=0`

• The marker and link filters have been added for the `inventory` & `wikilist` commands.
  *Example :* `inventory link=5 marker="bottom,top"` [This will allow you to retrieve all link cards that have a link value of 5 and have low and high markers.]

• The `scale` filter has been added for `inventory` & `wikilist` commands.
  *Example :* `inventory scale=>5` [This will allow you to retrieve all the pendulum cards that have their scale greater than 5]

⇰ **Achievements**

• All achievements are now updated automatically.

• New achievements have emerged.

⇰ **Factory**

• The type of rarity of the monster cards now influences the energy saving of your factory.

• Token' cards now allow you to increase your storage capacity. +20 per card placed. You will lose one card per day and you can place a maximum of 10 cards.

• Pendulum type cards allow to increase 2000 times the value of their scale, the maximum energy of the plant. You will lose 10% of your invested bonus energy points per day and you can put a maximum of 5 pendulum cards and/or your factory level multiplied by 5000.

• Auto-fill has been implemented to automatically fill your plant with the missing cards.
  **WARNING** Auto-fill only works on cards that you have in multiple copies. It also makes no distinction between rare cards. If you want to secure your cards, remember to block them with the "lock".
  *Example :* `factory autofill`

• The ability to block or unblock any card with the arguments `lock` and `unlock` in order to take it into account or not in the factory auto-fill.
  *Example :* `factory lock card_id.rarity ...` | `factory unlock card_id.rarity ...`

⇰ **Badges**

• Badges are available to players who meet certain conditions !

```yml
Millionaire: Reaching the million mark.
Jackpot: Get the jackpot at the RollMachine.
Staff: Be part of our team.
Translator: Correct mistakes or make translations for new languages.
Collector: Have all the cards.
Donor: Make a donation (Level 1: <= 10 USD, Level 2: <= 50 USD, Level 3: > 50 USD)
Crazy Voter: Vote 60 times during the month.
Support: Be on the support server.
Classement: To be in the top 3 players.
```

⇰ **Votes**

• Retrieve a quest by voting on top.gg: **[[voter]](https://top.gg/bot/672416519912947732/vote)**

⇰ **Profile**

• Your ranking now appears on your profile.

• The resulting badges appear on the profile.

---

# CORRECTIONS

⇰ **Alarm**

• The time on the `secretword` alarm has been corrected. The notification will now be sent as soon as the office is open.

⇰ **Filters**

• The rarity filter has been modified in order to be able to stipulate several rarities.
  *Example :* `inventory rarity="common,super rare"` [This will allow you to recover all your cards with the `common` & `super rare` rarities.]
  *It is of course possible to do the same with the `wikilist` command as well as adding `!` at the beginning to retrieve everything that is not `common` and `super rare`.*

⇰ **Settings**

• The option to change the location of images on card information also applies to your profile and the **YGiPass** reward.
  *Example :* `settings image big` [This will make all your images look great.]

⇰ **Icons**

• The icon for the pendulum scale has been corrected on the pendulum map information.

⇰ **Quests**

• The quest information is now displayed when you win it at the **RoleMachine**.

• The number of remaining quests now appears on the command `quests`.

⇰ **Factory**

• The correct information for the card you are using to recharge your plant will now appear.

• Information on the number of missing cards now appears on your plant display.
