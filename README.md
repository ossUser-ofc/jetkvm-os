# jetkvm-os 
I am trying to get a simple porteus running as a 'jetkvm os'
This is work in progress. BUT I WILL PROVIDE A SIMPLE FLOWCHART :)

# JetKVM Client Boot Flow (Porteus Kiosk)

### Notes
- Single-color default Mermaid styling
- Minimal boot-to-JetKVM flow
- GitHub-compatible

Credits: https://github.com/jetkvm/website, https://porteus-kiosk.org

```mermaid
flowchart TD
    A[Power On] --> B[Porteus Kiosk Boot]
    B --> C[Linux Kernel]
    C --> D[Network Ready]
    D --> E[Browser Kiosk Mode]
    E --> F[JetKVM Web Interface]
