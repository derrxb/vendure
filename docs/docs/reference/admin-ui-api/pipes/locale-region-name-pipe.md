---
title: "LocaleRegionNamePipe"
weight: 10
date: 2023-07-21T07:17:04.807Z
showtoc: true
generated: true
---
<!-- This file was generated from the Vendure source. Do not modify. Instead, re-run the "docs:build" script -->
import MemberInfo from '@site/src/components/MemberInfo';
import GenerationInfo from '@site/src/components/GenerationInfo';
import MemberDescription from '@site/src/components/MemberDescription';


## LocaleRegionNamePipe

<GenerationInfo sourceFile="packages/admin-ui/src/lib/core/src/shared/pipes/locale-region-name.pipe.ts" sourceLine="18" packageName="@vendure/admin-ui" />

Displays a human-readable name for a given region.

*Example*

```HTML
{{ 'GB' | localeRegionName }}
```

```ts title="Signature"
class LocaleRegionNamePipe extends LocaleBasePipe implements PipeTransform {
  constructor(dataService?: DataService, changeDetectorRef?: ChangeDetectorRef)
  transform(value: any, locale?: unknown) => string;
}
```
* Extends: <code>LocaleBasePipe</code>


* Implements: <code>PipeTransform</code>



<div className="members-wrapper">

### constructor

<MemberInfo kind="method" type="(dataService?: <a href='/docs/reference/admin-ui-api/providers/data-service#dataservice'>DataService</a>, changeDetectorRef?: ChangeDetectorRef) => LocaleRegionNamePipe"   />


### transform

<MemberInfo kind="method" type="(value: any, locale?: unknown) => string"   />




</div>