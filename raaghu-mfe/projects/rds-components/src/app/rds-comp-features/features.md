---
slug: "/comp-features"
date: "2019-05-04"
title: "Components > Features"
---


### Features

<p>provides a table based on requirement and actions needed by the user</p>

<section class="py-4">
    <h6>Default</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewBasic-tab" data-bs-toggle="tab" data-bs-target="#PreviewBasic" type="button" role="tab" aria-controls="PreviewBasic" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularBasic-tab" data-bs-toggle="tab" data-bs-target="#AngularBasic" type="button" role="tab" aria-controls="AngularBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewBasic" role="tabpanel" aria-labelledby="PreviewBasic-tab">
         <div class="contents  p-5">
              <div class="row">
              <div class="col-md-12">
                  <img src="/images/edition-list.png" class="img-fluid w-100">
            </div>
          </div>
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic" role="tabpanel" aria-labelledby="AngularBasic-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
  <rds-comp-features
  [EditionsTableHeader]="EditionsTableHeader"
  [EditionsTableData]="EditionsTableData"
  [recordsPerpage]="10"
  EditionName=""
  [AnnualPrice]="200"
  [TrailPeriod]="10"
  [ExpiryInterval]="10"
  freeEditon="Edition"
  [featureList]="featureList"
></rds-comp-features>
```
</div>
</div>
  </div>
        </div>
      </div>
    </div>
  </section>
   