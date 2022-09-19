# MBV-Product-Card

Este es un paquete de pruebas de despliegue en NPM

## Ejemplo

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'mbv-product-card';
```

```
<ProductCard
        key={product.id}
        product={product}
        initialValues={{
          count: 4,
          maxCount: 10,
        }}
      >
        {({ reset, increaseBy, count, isMaxCountReached, maxCount }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
      </ProductCard>
```
