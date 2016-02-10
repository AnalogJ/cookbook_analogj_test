# test_cookbook-cookbook

TODO: Enter the cookbook description here.

## Supported Platforms

TODO: List your supported platfor

ms.





## Attributes

<table>
  <tr>
  
  
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['test_cookbook']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### test_cookbook::default

Include `test_cookbook` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[test_cookbook::default]"
  ]
}


```

## License and Authors

Author:: Copyright 2014, Adobe Systems Incorporated (<serenity@adobe.com>)
