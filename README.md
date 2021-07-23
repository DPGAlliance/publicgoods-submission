[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](code_of_conduct.md)

# Digital Public Goods Submission Form

This repository contains the source code for the custom submission form available at the two following addresses:
* https://submission.digitalpublicgoods.net
* https://digitalpublicgoods.net/submission (which redirects to the one above)

This submission form is made available to collect the necessary information on digital solutions that want to be considered as digital public goods and included in the [Digital Public Goods Registry](https://digitalpublicgoods.net/registry). For information on how to submit a nomination to the DPG Registry, see our [submission guide](https://digitalpublicgoods.net/submission-guide/).

## 👀 Overview

The submission form is a web application (webapp) built using [Next.js](https://nextjs.org/) as a React Framework and deployed using [Vercel](https://vercel.com/). 

The forms are [Data Driven Forms](https://data-driven-forms.org/), configured through this JSON schema: [schema.js](schemas/schema.js).

## :memo: License

This software is licensed under the [Apache License 2.0](LICENSE):

```
   Copyright 2021 UNICEF

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```

The two main dependencies (and their respective licenses) this software depends on are:
* [Next.js](https://nextjs.org/) licensed under the MIT License
* [Data Driven Forms](https://data-driven-forms.org/) licensed under the Apache License 2.0
