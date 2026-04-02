# Xianyu Auto Ops Playbook

## 1. Best trigger examples

Use this skill for requests like:

- 帮我写一个闲鱼商品文案，中英文双语
- 把这段产品介绍改成闲鱼更容易成交的版本
- 给我 10 个闲鱼标题
- 为这个二手商品做一套自动运营 SOP
- Write a Xianyu listing package for this product
- Turn these product specs into an Idle Fish sales post

## 2. Information to collect

Ask for or infer:

- product name / category
- brand
- condition
- age / usage frequency
- flaws
- accessories included
- shipping / pickup method
- target city
- desired price
- urgency to sell

If 20-30% of inputs are missing, continue with assumptions instead of blocking.

## 3. Title patterns

### Chinese title patterns

1. `品牌名 + 商品名 + 成色说明 + 适合谁`
2. `低价转 + 商品名 + 功能亮点 + 自提/包邮`
3. `闲置出 + 商品名 + 配件齐全 + 性价比高`

### English title patterns

1. `Brand + item + condition + use case`
2. `Affordable + item + key benefit`

## 4. Description formula

### Chinese

Use this order:

1. 开头一句说明是什么
2. 为什么出 / 为什么值得买
3. 成色与瑕疵说明
4. 配件、发货、自提信息
5. 友好成交收口

### English

Compress into:

1. item summary
2. condition
3. delivery / bundle
4. action line

## 5. Reply template bank

### 还在吗
在的，商品还在，方便的话我可以把细节图/使用情况再发你看。  
Still available. I can also share more detail photos if you want.

### 最低多少
这个价格已经按成色和配件压过一轮了，真心想要的话可以小刀，但不适合砍太狠。  
The current price is already fairly adjusted. Small negotiation is okay if you're serious.

### 有瑕疵吗
有，已经在描述里写明了，主要是___，不影响正常使用。我也可以补近照给你确认。  
Yes, the flaw is disclosed clearly. It mainly is ___ and does not affect normal use. I can send close-up photos.

### 包邮吗
看地区，近一点可以包，偏远地区可能需要补一点运费。  
Depends on location. Nearby shipping may be included; remote areas may need extra shipping.

### 成交推进
如果你这边确定要，我可以今天帮你保留/安排发出。  
If you want it, I can reserve it for you and arrange shipping today.

## 6. Image prompt formula

For AI-generated cover visuals, use:

`clean marketplace product cover, realistic product-centered composition, neutral or lightly branded background, clear lighting, no clutter, trustworthy second-hand sale style, high click-through visual hierarchy`

For upgraded promotional style, use:

`premium resale marketplace hero image, product-centered layout, strong contrast, clean typography-safe negative space, realistic details, platform-friendly composition`

## 7. Batch mode

When the user gives multiple products:

- keep each item compact
- one title set + one short description + one price idea + one reply note per SKU
- avoid writing long essays for every item

## 8. Suggested MVP extensions

A more executable future version of this skill can add:

- CSV / spreadsheet import
- batch listing generation scripts
- image prompt presets by category
- category-specific reply packs
- publishing payload adapters for marketplace tools
