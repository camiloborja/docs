# Ecredit 🍂

This custom development allows us to bring in order information to display installment details if eCredit is approved. This development works for the orderPlaced event.

## Setup 🔧

### Adding to the store theme

In the `manifest.json` of your store theme add the following dependency:

```json
{
  "dependencies": {
     "marcimex.jobs-page": "0.x",
  }
}
```

Now you can use all the components of the `Ecredit` app.

| Name          | Description                                     |
| ------------- | ----------------------------------------------- |
| `EcreditOrderPlaced` | This is the main component responsible for receiving the information and executing the corresponding logic to display the information if eCredit is approved. |
| `getDocuments` | Component responsible for fetching all order-related information through GraphQL. |

## Examples 🧤

```json
{
  "op-header": {
    "children": [
      "custom-ecredit",
    ]
  }
}
```

## Used by 🛸

This project is being used by the following stores

- Marcimex

## Contributors 👷

<table>
  <tr>
    <td align="center">
      <img src="https://marcimex.vtexassets.com/arquivos/2024-05-25-documentation.jpg" width="120px" alt="Contributor Picture"/>
      <br />
      <sub>
        <b>Camilo Borja</b>
      </sub>
      <br />
      <a href="mailto:camilo@jumpdigital.co" title="Correo empresarial">💻 camilo@jumpdigital.co</a>
    </td>
  </tr>
</table>

Copyright Jump Digital 2024
