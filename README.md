# MERMAID
FASFFASAFS

``` mermaid

classDiagram
    class Producto {
        -_codigo: str
        -_proveedor: str
        -_linea: str
        -_marca: str
        -_producto: str
        -_personal: float
        -_mayorista: float
        -_cantidad: int
        +__init__(codigo: str, proveedor: str, linea: str, marca: str, producto: str, personal: float, mayorista: float, cantidad: int): void
    }
    class Bodega {
        -_producto: Producto
        +__init__(producto: Producto): void
        +mostrar_productos_y_restar(): void
    }
    class Agenda {
        -_descripcion: str
        +__init__(codigo: str, proveedor: str, marca: str, descripcion: str, personal: float, mayorista: float, cantidad: int): void
    }
    class Color {
        -_descripcion: str
        +__init__(codigo: str, proveedor: str, marca: str, descripcion: str, personal: float, mayorista: float, cantidad: int): void
    }
    class Micropunta {
        -_descripcion: str
        +__init__(codigo: str, proveedor: str, marca: str, descripcion: str, personal: float, mayorista: float, cantidad: int): void
    }
    class Tajalapiz {
        -_descripcion: str
        +__init__(codigo: str, proveedor: str, marca: str, descripcion: str, personal: float, mayorista: float, cantidad: int): void
    }
    class Archivador {
        -_descripcion: str
        +__init__(codigo: str, proveedor: str, marca: str, descripcion: str, personal: float, mayorista: float, cantidad: int): void
    }
    class Borrador {
        -_descripcion: str
        +__init__(codigo: str, proveedor: str, marca: str, descripcion: str, personal: float, mayorista: float, cantidad: int): void
    }
    class Cosedora {
        -_descripcion: str
        +__init__(codigo: str, proveedor: str, marca: str, descripcion: str, personal: float, mayorista: float, cantidad: int): void
    }
    class Cuaderno {
        -_descripcion: str
        +__init__(codigo: str, proveedor: str, marca: str, descripcion: str, personal: float, mayorista: float, cantidad: int): void
    }
    class Esfero {
        -_descripcion: str
        +__init__(codigo: str, proveedor: str, marca: str, descripcion: str, personal: float, mayorista: float, cantidad: int): void
    }
    class JuegoGeometrico {
        -_descripcion: str
        +__init__(codigo: str, proveedor: str, marca: str, descripcion: str, personal: float, mayorista: float, cantidad: int): void
    }
    class Lapiz {
        -_descripcion: str
        +__init__(codigo: str, proveedor: str, marca: str, descripcion: str, personal: float, mayorista: float, cantidad: int): void
    }

    Bodega --> Producto
    Bodega <|-- Agenda
    Bodega <|-- Color
    Bodega <|-- Micropunta
    Bodega <|-- Tajalapiz
    Bodega <|-- Archivador
    Bodega <|-- Borrador
    Bodega <|-- Cosedora
    Bodega <|-- Cuaderno
    Bodega <|-- Esfero
    Bodega <|-- JuegoGeometrico
    Bodega <|-- Lapiz

```
