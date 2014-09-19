# base_image-cookbook

TODO: Enter the cookbook description here.

## Supported Platforms

TODO: List your supported platforms.

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['base_image']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### base_image::default

Include `base_image` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[base_image::default]"
  ]
}
```

## License and Authors

Author:: YOUR_NAME (<YOUR_EMAIL>)
