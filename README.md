# MG6
1. The entire for loop will complete before the Update method finishes. It will make the game lag.

2. When the cat starts falling, it may be able to jump again even without landing on a platform. This is because we enable the collider while falling, and any collision with a platform can set _isGrounded to true, even if the cat isn't standing on it.