FastBoost

FastBoost is a lightweight Windows optimization tool with a clean, compact interface for quickly applying advanced performance tweaks.
It eliminates the need to manually edit the registry or type complex commands by providing simple one-click toggles.
✨ Features

    Windows Autotuning – Switch between DISABLE and NORMAL TCP autotuning.

    NetworkThrottlingIndex – Set to 0xFFFFFFFF (disable throttling) or 10 (default).

    SystemResponsiveness – Set to 0 (maximum responsiveness for foreground tasks) or 20 (default).

    BCDEdit Tweaks – Toggle advanced boot configuration options:

        useplatformclock

        useplatformtick

        disabledynamictick

        tscsyncpolicy

    Microsoft Game Input Service – Enable or disable the GameInputSvc service.

    Lock GPU Clock – Force GPU clocks to remain constant.

    Unpark CPU Cores – Keep all CPU cores active at all times.

other possible tweaks : 

sc config GraphicsPerfSvc start= disabled
sc stop XblAuthManager
sc config XblAuthManager start= disabled  

sc stop DiagTrack
sc config DiagTrack start= disabled

🖼️ Interface

    Minimal dark-theme design.

    All settings presented in a single, easy-to-read list.

    Two-button toggles for fast configuration (DISABLE/NORMAL, 0xFFFFFFFF/10, 0/20, etc.).

    Recommended options highlighted for quick access.

⚠️ Requirements

    Windows 10/11.

    Administrator privileges (UAC prompt on launch).

📦 Usage

    Download the latest FastBoost.exe from the Releases page.

    ## 💖 Support the project

If you like this app and want to support my work, you can donate via Stripe:

[![Donate via Stripe](https://img.shields.io/badge/Donate-Stripe-blue.svg)](https://buy.stripe.com/6oU5kC3bKaMW2KKeQe7g401)


    Run it — Windows will prompt for administrator approval.

    Click the desired buttons to apply settings.
    Each action shows the system’s response in a popup window.
