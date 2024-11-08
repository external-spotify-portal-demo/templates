```mermaid
flowchart LR;
    A["External internet"]
    B["CloudFlare"]
    C["Ingress Network Firewall"]
    D["App/Webgateway"]
    E["East-West Network Firewall"]
    F["Kohoapi vpc"]
    G["Cardholder Data Environment"]
    A-->B;
    B-->C;
    C-->D;
    D-->E;
    E-->G;
    E-->F;
```
