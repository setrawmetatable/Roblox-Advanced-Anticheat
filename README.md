# Roblox-Advanced-Anticheat

Hello.

Since hyperion has been living up to it's purpose and all executors are now confirmed detected, and with the really low chances of a synapse x type executor popping up in the future.

I have decided to opensource my anticheat I have used in my games.

Because hyperion will be doing it's job and my anticheat is not worth gatekeeping anymore.

I would like to introduce to you....

SQUEEKHUB ANTICHEAT!! or anti-executor and anti-coregui... but let's just call it an anticheat. Cause it is one.

This compact anticheat solution is designed to effectively protect your game from exploiters with minimal setup. Simply place the provided server script into ServerScriptService, and it will automatically load all necessary components.

## **Features**
- Executor Detection: Identifies exploiters by leveraging vulnerabilities in common executors, such as Celery's hook into OpenCloudService. The anticheat scans all game descendants for suspicious instances like "OpenCloudService."

- CoreGui Detection: Preloads game.CoreGui to retrieve asset IDs of all instances within CoreGui, enabling the detection of popular scripts like Infinite Yield and Hydroxide that use custom asset IDs or images.

- Admin Panel and Webhook Integration: The anticheat includes a customizable admin panel and a Discord webhook for notifications. You can configure the webhook URL in the "MainAnticheatHandler" and set your user ID in the "Client" script to restrict admin access.

- Webhook Alerts: Sends notifications to your Discord server when:

  - A player is banned or unbanned.
  - A player is flagged.
  - A banwave is initiated.
- Manual Banwave Control: Instead of automatically banning cheaters, the anticheat maintains a list of detected cheaters. You can review and ban everyone in the list by triggering a banwave from the admin panel.

## **Advantages**
This anticheat provides robust protection against script kiddies and stops 99% of exploiters, ensuring a fair gameplay experience for all.

This anticheat runs on an actor meaning it would be impossible for exploiters to hook into anything in the script's environment, unless they use an exploit function called "run_on_actor". But that won't happen due to the lack of executors that support that function. (Yes Synapse Z has it but it's really shit and the executor is ULTRA DETECTED.)

Enjoy a more secure game with this powerful tool!
