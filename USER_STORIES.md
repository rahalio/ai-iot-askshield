# AskShield — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### SOC annotator

- As an annotator, I want a short daily queue of the most uncertain flows, so my time moves the model instead of random sampling.
- As an annotator, I want a plain reason for each query, so I understand why the system bothered me.
- As an annotator, I want redacted payloads by default, so I am not reading badge or patient device contents.

### Detection engineer

- As a detection engineer, I want to compare uncertainty sampling versus query-by-committee on our capture, so I pick a strategy with data not folklore.
- As a detection engineer, I want accuracy-versus-labels charts, so I can stop labeling when the curve flattens.

### Wireless network admin

- As a wireless admin, I want capture points registered per SSID/site, so industrial and guest traffic are not mixed in one model.

### Model operator

- As a model operator, I want poison alerts when a single annotator’s labels swing metrics abnormally, so we catch mistakes or malice.
- As a model operator, I want rollback to the last model before a bad labeling batch, so production detection survives human error.

### Security administrator

- As a security admin, I want a hard cap on labels per day per team, so active learning cannot become unpaid overtime.
- As a security admin, I want dual annotator review for DoS/safety classes, so one misclick cannot disable a plant WLAN defense.
