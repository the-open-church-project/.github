# Local and offline operation roadmap

This proposed shared capability will let Verger and Open Worship use local
storage, local models, and offline workflows where practical. Local operation is
intended to improve reliability and reduce the movement of service audio and
other private church data off device.

## Status

Proposed. No packaged application or local model bundle is documented yet.

## Roadmap

```mermaid
flowchart LR
    A["NOW<br/>Define local data and hardware needs"]
    B["NEXT<br/>Run the core workflow offline"]
    C["TEST<br/>Validate startup and failure recovery"]
    D["LATER<br/>Package updates and hardware guidance"]
    A --> B --> C --> D
```

### Now

- Define local storage for Verger church data, approved Open Worship scripture
  texts and presentations, settings, and models.
- Set minimum hardware, storage, microphone, and projector requirements.
- Document which licenses permit offline use and redistribution.
- Decide what, if anything, can be synchronized when internet access is
  available.

### Next

- Run Open Worship recognition and presentation without an internet connection.
- Define which Verger workflows can work locally or through self-hosting.
- Add visible offline status and a clear manual fallback.
- Test startup, microphone failure, display failure, and interrupted updates.
- Provide a secure, reversible data import and backup process.

### Later

- Package a supported local installer and optional model downloads.
- Offer signed updates without making internet access necessary during services.
- Document supported hardware and maintain an operator recovery guide.

## Open questions

- What hardware is realistic for the project’s first partner churches?
- How large may local scripture and speech model data be?
- Which updates require an internet connection, and which can be carried on
  removable media?
