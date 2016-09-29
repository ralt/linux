===================================
Support multiple virtual interfaces
===================================

TBD

Note: WDS with identical MAC address should almost always be OK

Insert notes about having multiple virtual interfaces with different
MAC addresses here, note which configurations are supported by
mac80211, add notes about supporting hw crypto with it.

.. kernel-doc:: include/net/mac80211.h
   :functions: ieee80211_iterate_active_interfaces ieee80211_iterate_active_interfaces_atomic
