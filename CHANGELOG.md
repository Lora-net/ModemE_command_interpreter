# Modem-E Interpreter CHANGELOG


## v0.8 (2026-09)

This versions works with Modem-E version 2.1.1.

### Newly added commands

These 4 commands are generic commands:

- get_channel_mask
- set_channel_mask
- get_no_rx_packet_threshold
- set_no_rx_packet_threshold

These 3 commands are dedicated for ABP:

- debug_connect_with_abp
- modem_backup_retention_ram_in_nvm
- modem_restore_retention_ram_from_nvm

And below 2 commands are generic ones but in fact only make sense to be used together with the 2 nvm related commands:

- disable_event_process
- enable_event_process

### Changes

- command `set_nwk_key` renamed to `set_app_key`.
- command `set_app_key_multicast` renamed to `set_gen_app_key`.


## v0.7.3 (2024-09)

First public released version, based on Modem-E version 2.0.1.
