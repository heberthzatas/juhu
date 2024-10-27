# Protocolo de Transferencia de Embriones (TE) Tradicional

```mermaid
flowchart TD
    subgraph Donadora
        A1(Selección -30 a -60 días)
        A2(Preparación -20 días)
        A3(Sincronización con Prostaglandina - Día 0)
        A4(Superovulación con FSH - Días 1 a 4)
        A5(Segunda Prostaglandina - Día 6)
        A6(Inseminación - Día 7)
        A7(Recolección de Embriones - Día 14)
    end
    
    subgraph Receptora
        B1(Selección -30 a -60 días)
        B2(Preparación -20 días)
        B3(Sincronización con Prostaglandina - Día 0)
        B4(Segunda Prostaglandina - Día 6)
        B5(Transferencia de Embriones - Día 14)
    end

    A1 --> A2 --> A3 --> A4 --> A5 --> A6 --> A7
    B1 --> B2 --> B3 --> B4 --> B5
    A7 --> B5
