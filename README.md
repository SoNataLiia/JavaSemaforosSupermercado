# Supermercado – Semáforos

## Descripción

Simulación de un supermercado con control de aforo y cajas.

## Restricciones

* Máximo 15 clientes en la tienda
* 3 cajas disponibles
* 1 cliente por caja

## Objetivo

* Controlar acceso a la tienda
* Controlar uso de cajas
* Calcular dinero total y por caja

## Concurrencia

* N hilos (clientes)
* Semaphore(15) → limita acceso a la tienda
* Semaphore(3) → controla las cajas
* Semaphore(1) → protege variables compartidas (mutex)

## Estructura

* Clase `Supermercado` → main y variables globales
* Clase `Cliente` → hilo que simula compra

## Resultado

* Dinero total
* Dinero por cada caja
