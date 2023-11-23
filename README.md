# JP-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Jeypi

## Ejemplo

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'jp-product-card';
```

```
<ProductCard
        product={product}
        initialValues={{
          count: 4,
          maxCount: 15,
        }}
      >
        {({ reset, count, increaseBy, isMaxCountReached, maxCount }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
      </ProductCard>
```