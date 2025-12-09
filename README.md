# Ejercicio-5-XML

    <?xml version="1.0" enconding="UTF-8"?>
    <ticket id="TCK-00123">
    <fecha>2025-01-16</fecha>
    <hora>18:43</hora>

    <!-- Datos de pago -->
    <pago moneda="EUR">
        <precioSinIVA>48.00</precioSinIVA>
        <cantidadIVA>10.08</cantidadIVA>
        <pvpTotal>58.08</pvpTotal>

        <formaPago tipo="tarjeta">
            <tarjeta tipo="Visa">************4821</tarjeta>
        </formaPago>
    </pago>

    <!-- Datos del cliente -->
    <cliente>
        <nombre>Laura Méndez Ortiz</nombre>
    </cliente>

    <!-- Datos del comercio -->
    <comercio>
        <nombre>Supermercados La Estrella</nombre>
        <direccion>Calle Mayor 24, 1ºA, 28013 Madrid</direccion>
        <cif>B12345678</cif>
        <telefono>912345678</telefono>
    </comercio>

    <!-- Líneas de la compra -->
    <compra>
        <lineaCompra>
            <articulo>Leche entera 1L</articulo>
            <cantidad>2</cantidad>
            <precioUnitario>0.90</precioUnitario>
            <iva>0.19</iva>
            <pvp>2.18</pvp>
        </lineaCompra>

        <lineaCompra>
            <articulo>Café molido 250g</articulo>
            <cantidad>1</cantidad>
            <precioUnitario>3.50</precioUnitario>
            <iva>0.74</iva>
            <pvp>4.24</pvp>
        </lineaCompra>

        <lineaCompra>
            <articulo>Pan barra</articulo>
            <cantidad>3</cantidad>
            <precioUnitario>0.45</precioUnitario>
            <iva>0.28</iva>
            <pvp>1.63</pvp>
        </lineaCompra>
        
    </compra>

</ticket>
