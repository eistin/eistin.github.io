---
title: Import
weight: 30
menu:
  notes:
    name: Import
    identifier: notes-tf-import
    parent: notes-tf-basics
    weight: 30
---

<!-- Import Resource -->
{{< note title="Import Resource">}}

```shell
terraform import aws_instance.foo i-abcd1234
```

{{< /note >}}

<!-- Import Module -->

{{< note title="Import Module" >}}

```shell
terraform import module.foo.aws_instance.bar i-abcd1234
```

{{< /note >}}

<!-- Import into Resource configured with count -->

{{< note title="Import into Resource configured with count" >}}

```shell
terraform import 'aws_instance.baz[0]' i-abcd1234
```

{{< /note >}}