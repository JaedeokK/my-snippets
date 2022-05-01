# My Snippet!

This may or may not help you.\
These are actually my snippets, not just my snippets by name.\
It will be updated as per my needs and no support for the feature will be provided.\
This means I can add or remove features and modify existing ones as my needs.

## Snippets
### React(ts)
| Snippet | Renders                                          |
| ------- | ------------------------------------------------ |
| `fc`    | Functional Component                             |
| `ifc`   | Import(FC) Functional Component                  |
| `efc`   | Export Functional Component                      |
| `iefc`  | Import(FC) Export Functional Component           |
| `fce`   | Functional Component Export Default              |
| `ifce`  | Import(FC) Functional Component Export Default   |

### Next.js(ts)
| Snippet | Renders                                          |
| ------- | ------------------------------------------------ |
| `np`    | Next Page                                        |
| `gsp`   | Get Static Props                                 |
| `gssp`  | Get Server Side Props                            |

### Utils(js, ts)
| Snippet | Renders                                          |
| ------- | ------------------------------------------------ |
| `af`    | Arrow Function                                   |
| `fc`    | ClassName Bind                                   |
| `ifc`   | Console                                          |
| `efc`   | Console Error                                    |
| `iefc`  | Console Log                                      |
| `fce`   | Console Table                                    |


## Full Expansions

### React(ts)
#### fc - Functional Component

```typescript
  interface |Props {
    |
  };

  const |: FC<|Props> = (props) => {
   return (|);
  };
```

#### ifc - Import FC / Functional Component

```typescript
  import { FC } from 'react';

  interface |Props {
    |
  };

  const |: FC<|Props> = (props) => {
   return (|);
  };
```

#### efc - Export Functional Component

```typescript
  interface |Props {
    |
  };

  export const |: FC<|Props> = (props) => {
   return (|);
  };
```

#### iefc - Import FC / Export Functional Component

```typescript
  import { FC } from 'react';

  interface |Props {
    |
  };

  export const |: FC<|Props> = (props) => {
   return (|);
  };
```

#### fce - Functional Component Export Default

```typescript
  interface |Props {
    |
  };

  const |: FC<|Props> = (props) => {
   return (|);
  };

  export default |;
```

#### ifce - Import FC, Functional Component Export Default

```typescript
  import { FC } from 'react';

  interface |Props {
    |
  };

  const |: FC<|Props> = (props) => {
   return (|);
  };

  export default |;
```

### Next.js(ts)

#### np - Next Page

```typescript
  import { NextPage } from 'next'
  import { useTranslation } from 'next-i18nex';

  interface |Props {
    |
  };

  const |: NextPage<|Props> = (props) => {
    const { t } useTranslation(`|`);

    return (|);
  };

  export default |;
```

#### gsp - Get Static Props

```typescript
  import { serverSideTranslations } from 'next-i18next/serverSideTranslations';

  export const | = async ({ locale }): MyGetStaticPropsContext|) => {
    |
    return {
      props: {
        ...(await serverSideTranslation(locale ['common' |],
        |
      }
    };
  };
```

#### gssp - Get Server Side Props

```typescript
  import { serverSideTranslations } from 'next-i18next/serverSideTranslations';

  export const | = async ({ locale }): MyGetServerSidePropsContext|) => {
    |
    return {
      props: {
        ...(await serverSideTranslation(locale ['common' |],
        |
      }
    };
  };
```

### Utils(js, ts)

#### af - Arrow Function

```javascript
  const | = (|) => {|};
```

#### cx - ClassName Bind

```javascript
  import classNames from 'classnames/bind';
  import styles from './$1.module.scss';

  const cx = classNames.bind(styles);
```

#### co - Console

```javascript
  console.|(|);
```

#### ce - Console Error

```javascript
  console.error(|);
```

#### cl - Console Log

```javascript
  console.log(|);
```

#### ct - Console Table

```javascript
  console.table(|);
```
