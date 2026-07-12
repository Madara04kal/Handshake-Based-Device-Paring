This is the Mini project we do for our 4th semester module EE2080. What we do here is pair 2 devices via bluetooth through a real physical handshake.

<img width="1024" height="559" alt="WhatsApp Image 2026-07-12 at 18 18 33" src="https://github.com/user-attachments/assets/8c8a61b1-4818-4e02-a20c-c3e2ece8eb0f" />


1. Setup
Init Hardware & BLE
2. Initialization
Register BLE Services
3. IDLE State
LED: Breathing Green
4. beginHandshake()
Send MSG_TRIGGER
5. CAPTURING
Capture Local Data (4s)
6. WAITING_FOR_PEER
Wait Rx / Timeout (8s)
7. PROCESSING
Invert B, Run Correlation
8a. SUCCESS (KEY)
Key Extracted & Matched
8b. FAIL
Timeout: No Response
Active State
WAITING_FOR_PEER
Trigger Option
Boot Button
Waiting for Peer Data...
