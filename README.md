# SQC-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Snayder Charaña

## Ejemplo
```
    import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'do-product-card';
```

```
  <ProductCard
    product={product}
    initialValues={{
      count: 4,
      maxCount: 10,
    }}
  >
    {({ reset, increaseBy, count, isMaxCountReached }) => (
      <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />
      </>
    )}
  </ProductCard>
```
