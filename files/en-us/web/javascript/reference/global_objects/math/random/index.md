---
title: Math.random()
slug: Web/JavaScript/Reference/Global_Objects/Math/random
page-type: javascript-static-method
browser-compat: javascript.builtins.Math.random
---

{{JSRef}}

The **`Math.random()`** static method returns a floating-point, pseudo-random number that's greater than or equal to 0 and less than 1, with approximately uniform distribution over that range — which you can then scale to your desired range. The implementation selects the initial seed to the random number generation algorithm; it cannot be chosen or reset by the user.

> **Note:** `Math.random()` _does not_ provide cryptographically secure random numbers. Do not use them for anything related to security. Use the Web Crypto API instead, and more precisely the {{domxref("Crypto/getRandomValues", "window.crypto.getRandomValues()")}} method.

