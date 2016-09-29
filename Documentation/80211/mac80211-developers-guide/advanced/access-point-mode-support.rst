=========================
Access point mode support
=========================

TB

Some parts of the if_conf should be discussed here instead.

Insert notes about VLAN interfaces with hw crypto here or in the hw
crypto chapter.

Support for powersaving clients
===============================

.. kernel-doc:: include/net/mac80211.h
   :doc: AP support for powersaving clients

.. kernel-doc:: include/net/mac80211.h
   :functions: ieee80211_get_buffered_bc ieee80211_beacon_get ieee80211_sta_eosp ieee80211_frame_release_type ieee80211_sta_ps_transition ieee80211_sta_ps_transition_ni ieee80211_sta_set_buffered ieee80211_sta_block_awake
