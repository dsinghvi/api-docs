# 🔒 Smart Locks

### What is a Smart Lock?

Smart locks utilize technology to provide a new way to unlock or lock your door. With smart locks, you can access your premises without a physical key.

These locks can be integrated into various entry points, such as standard doors, gates, garage doors, elevators, and lockers. Some associated devices, such as intercoms and access control systems, come equipped with built-in video cameras and microphones. This way, you can see and communicate with whoever’s at your door, even when you're away from the location.

Seam's API provides the capability to lock and unlock doors remotely. For locks equipped with keypads, our API also permits the creation and programming of access codes.

### What is an Access Code?

An access code is a numeric or alphanumeric code that a user enters to gain access through the lock. Here's how it works:

* The smart lock owner sets a specific code for the lock.
* When the correct code is entered on the keypad, the lock releases and allows access.
* Access codes can be permanent (for homeowners or primary users) or temporary (for guests or service providers).

### **Use Cases**

Leverage Seam's API for the following applications:

1. **Shareable Web Pass:** Create a web pass to distribute to guests or visitors. When this pass is used, it can lock or unlock the smart lock.
2. **Scheduled Access:** Grant time-bound access by providing temporary codes to guests, babysitters, or service personnel. For example, a cleaner with a schedule from 10 am to 12 pm on Tuesdays could be given a code valid only within that time frame.
3. **Security Monitoring:** Get real-time status updates on when the door is locked or unlocked.

### **Next Steps**

To learn how to trigger locks and unlocks on your locks, check out our guide [here](lock-and-unlock.md). For guidance on setting up Access Codes for your device, refer to our guide [here](access-codes.md). Additionally, you can check out our API Reference Guides for [Locking and Unlocking](../../api-clients/locks/), and for [Access Codes](../../api-clients/access-codes/).