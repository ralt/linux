=======================
Basic hardware handling
=======================

TBD

This chapter shall contain information on getting a hw struct
allocated and registered with mac80211.

Since it is required to allocate rates/modes before registering a hw
struct, this chapter shall also contain information on setting up the
rate/mode structs.

Additionally, some discussion about the callbacks and the general
programming model should be in here, including the definition of
ieee80211_ops which will be referred to a lot.

Finally, a discussion of hardware capabilities should be done with
references to other parts of the book.

.. kernel-doc:: include/net/mac80211.h
   :functions: ieee80211_hw ieee80211_hw_flags SET_IEEE80211_DEV SET_IEEE80211_PERM_ADDR ieee80211_ops ieee80211_alloc_hw ieee80211_register_hw ieee80211_unregister_hw ieee80211_free_hw
