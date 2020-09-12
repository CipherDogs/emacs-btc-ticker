Emacs xmr-ticker-mode
=====================

Emacs minor-mode to display current Monero price on the mode-line.

Installation
------------

Your .emacs file should looks like:

    (require 'xmr-ticker)

    ;;Optional: You can setup the fetch interval
    ;;default: 10 secs
    (setq xmr-ticker-api-poll-interval 10)

    ;;Enable btc-ticker-mode
    (xmr-ticker-mode 1)
