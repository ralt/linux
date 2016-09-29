===============================
Receive and transmit processing
===============================

What should be here
===================

TBD

This should describe the receive and transmit paths in mac80211/the
drivers as well as transmit status handling.

Frame format
============

.. kernel-doc:: include/net/mac80211.h
   :doc: Frame format

Packet alignment
================

.. kernel-doc:: net/mac80211/rx.c
   :doc: Packet alignment

Calling into mac80211 from interrupts
=====================================

.. kernel-doc:: include/net/mac80211.h
   :doc: Calling mac80211 from interrupts

functions/definitions
=====================

.. kernel-doc:: include/net/mac80211.h
   :functions: ieee80211_rx_status mac80211_rx_flags mac80211_tx_info_flags mac80211_tx_control_flags mac80211_rate_control_flags ieee80211_tx_rate ieee80211_tx_info ieee80211_tx_info_clear_status ieee80211_rx ieee80211_rx_ni ieee80211_rx_irqsafeieee80211_tx_status ieee80211_tx_status_ni ieee80211_tx_status_irqsafe ieee80211_rts_get ieee80211_rts_duration ieee80211_ctstoself_get ieee80211_ctstoself_duration ieee80211_generic_frame_duration ieee80211_wake_queue ieee80211_stop_queue ieee80211_wake_queues ieee80211_stop_queues ieee80211_queue_stopped
