# Smart Money Concept (SMC) Liquidity Sweep: အသေးစိတ် သုတေသနစာတမ်း

## အမှုဆောင်အကျဉ်းချုပ် (Executive Summary)

Smart Money Concept (SMC) နှင့် Inner Circle Trader (ICT) အခြေခံ အကြိုင်းအရာများတွင် **Liquidity Sweep (ငွေဖြစ်လွယ်မှု ဆွဲယူခြင်း သို့မဟုတ် Stop Hunt)** သည် အရေးကြီးဆုံးနှင့် အမြတ်အစွန်းအများဆုံး ရရှိနိုင်သော နည်းဗျူဟာတစ်ခု ဖြစ်သည်။ စျေးကွက်သည် အမှတ်မဲ့ ရွေ့လျားနေခြင်း မဟုတ်ဘဲ Liquidity ရှိရာ အရပ်သို့သာ အစဉ်တစိုက် ဦးတည်နေသည်။ အဖွဲ့အစည်းကြီးများ (Smart Money/Institutional Players) သည် ၎င်းတို့၏ ကြီးမားသော Order များကို ဖြည့်တင်းရန်အတွက် Retail Trader များ၏ Stop Loss များကို တမင်တကာ ထုတ်ယူလေ့ရှိသည်။ ဤလုပ်ဆောင်ချက်ကို Liquidity Sweep ဟု ခေါ်သည်။ ဤသုတေသနစာတမ်းသည် Liquidity Sweep ၏ သဘောတရားများ၊ အမျိုးအစားများ၊ Break of Structure (BOS) နှင့် ကွဲပြားချက်များ၊ အချိန်ကာလအလိုက် (Session-Based) Sweep များ၊ PO3 (Power of 3) Model နှင့် ဆက်စပ်မှု၊ နှင့် လက်တွေ့ Trade ဝင်ရာတွင် အသုံးချနိုင်သည့် အဆင့်မြင့် Entry Model များကို အသေးစိတ် တင်ပြထားသည်။

## မာတိကာ (Table of Contents)

1. **နိဒါန်း (Introduction to Liquidity Sweep)**
2. **Liquidity Sweep ၏ အခြေခံ သဘောတရားများနှင့် ယန္တရားများ (Core Foundations & Mechanics)**
   * ၂.၁ Buy Side Liquidity (BSL) နှင့် Sell Side Liquidity (SSL)
   * ၂.၂ Internal Range Liquidity (IRL) နှင့် External Range Liquidity (ERL)
3. **Liquidity Sweep နှင့် Break of Structure (BOS) ကွဲပြားချက်များ (Sweep vs Breakout)**
   * ၃.၁ Liquidity Sweep ၏ လက္ခဏာရပ်များ
   * ၃.၂ Stop Hunt နှင့် Inducement ကွဲပြားချက်များ
4. **အချိန်ကာလအလိုက် Liquidity Sweep များ (Session-Based Sweeps)**
   * ၄.၁ Asian Range Liquidity
   * ၄.၂ London Open (Judas Swing) Sweep
   * ၄.၃ New York Session Sweep
5. **PO3 (Power of 3) နှင့် Manipulation Cycle (AMD Model)**
   * ၅.၁ Accumulation (စုဆောင်းခြင်း)
   * ၅.၂ Manipulation (Liquidity Sweep အဆင့်)
   * ၅.၃ Distribution (ဖြန့်ဝေခြင်း)
6. **အဆင့်မြင့် Liquidity Sweep Strategies (Entry Models)**
   * ၆.၁ Order Block (OB) နှင့် Fair Value Gap (FVG) ပေါင်းစပ်ခြင်း
   * ၆.၂ Lower Timeframe (LTF) Confirmation
   * ၆.၃ SMT Divergence နှင့် ဆက်စပ်မှု
7. **Risk Management နှင့် စိတ်ပညာ (Psychology in Liquidity Sweeps)**
8. **နိဂုံး (Conclusion)**
9. **ကိုးကားစာရင်း (References)**

---

## အပိုင်း (၁) - နိဒါန်း (Introduction to Liquidity Sweep)

ဘဏ္ဍာရေးစျေးကွက်တွင် စျေးနှုန်းသည် အကြောင်းရင်း နှစ်ရပ်ကြောင့်သာ ရွေ့လျားသည်။ ပထမအချက်မှာ **Liquidity (Stop Losses/Pending Orders)** ကို သွားရောက်ရယူရန် ဖြစ်ပြီး၊ ဒုတိယအချက်မှာ **Imbalance (Fair Value Gap)** ကို ပြန်လည် ဖြည့်တင်းရန် ဖြစ်သည် [1]။ SMC Trader တစ်ယောက်အတွက် အရေးကြီးဆုံး မေးခွန်းမှာ "ငါ့ရဲ့ Stop Loss က ဘယ်မှာလဲ?" မဟုတ်ဘဲ "တခြားသူတွေရဲ့ Stop Loss က ဘယ်မှာလဲ?" ဖြစ်ရပါမည်။ သင်သည် Liquidity ဘယ်မှာရှိမှန်း မသိပါက၊ သင်ကိုယ်တိုင်သည်ပင် Liquidity ဖြစ်နေနိုင်ပါသည် [2]။

Liquidity Sweep ဆိုသည်မှာ စျေးနှုန်းသည် အရေးကြီးသော Level တစ်ခု (Swing High/Low, Equal Highs/Lows) ကို Wick ဖြင့် ခဏတာ ကျော်ဖြတ်ပြီး၊ Stop Loss များကို စားကာ မူလ ဦးတည်ရာသို့ ပြန်လှည့်လာခြင်း ဖြစ်သည် [3]။ ဤလုပ်ဆောင်ချက်သည် စျေးကွက်အတွင်းရှိ အဖွဲ့အစည်းကြီးများ၏ လိုအပ်ချက်ကြောင့် ဖြစ်ပေါ်လာရခြင်းဖြစ်သည်။ အဖွဲ့အစည်းကြီးများသည် ၎င်းတို့၏ အလွန်ကြီးမားသော Order များကို ဖြည့်တင်းရန်အတွက် အခြားကုန်သည်များ၏ Stop Loss များကို လိုအပ်သည်။ ၎င်းတို့ ဝယ်ယူရန်အတွက် တစ်စုံတစ်ယောက်က ရောင်းချပေးရမည်ဖြစ်ပြီး၊ ထိုရောင်းချပေးသူများမှာ Retail Trader များ၏ Stop Loss များပင် ဖြစ်သည် [2]။ ထို့ကြောင့် စျေးနှုန်းသည် Stop Loss များ စုဝေးရာ နေရာများသို့ သံလိုက်ကဲ့သို့ ဆွဲယူခံရပြီး၊ ထိုနေရာတွင် Liquidation ဖြစ်သွားစေသည်။

Liquidity Sweep သည် အဖွဲ့အစည်းကြီးများအတွက် မရှိမဖြစ် လိုအပ်သော ယန္တရားတစ်ခု ဖြစ်သည်။ အဘယ်ကြောင့်ဆိုသော် ၎င်းတို့သည် သိန်းသောင်းချီသော လောင်စာဆီ (Stocks, Currencies) ကို တစ်ကြိမ်တည်း ဝယ်ယူလိုက်ပါက စျေးနှုန်းသည် ရုတ်တရက် အလွန်အမင်း မြင့်တက်သွားမည် (Slippage)။ ထို့ကြောင့် ၎င်းတို့သည် စျေးနှုန်းကို တဖြည်းဖြည်းနှင့် ဆွဲယူရန်အတွက် စျေးကွက်အတွင်းရှိ ရှိပြီးသား Sell Orders များကို အသုံးချရသည်။ ထို Sell Orders များကို ရရှိရန် အကောင်းဆုံး နေရာမှာ Retail Trader များ၏ Stop Loss များ ဖြစ်သည်။

---

## အပိုင်း (၂) - Liquidity Sweep ၏ အခြေခံ သဘောတရားများနှင့် ယန္တရားများ

### ၂.၁ Buy Side Liquidity (BSL) နှင့် Sell Side Liquidity (SSL)

Liquidity Sweep ကို ခွဲခြားလေ့လာရာတွင် Buy Side Liquidity (BSL) နှင့် Sell Side Liquidity (SSL) ဟူ၍ အဓိကအားဖြင့် နှစ်မျိုး ခွဲခြားနိုင်သည် [4]။

*   **Buy Side Liquidity (BSL)**: ဤသည်မှာ စျေးကွက်၏ အထက်ပိုင်း (Swing Highs, Resistance Levels, Equal Highs) များတွင် ရှိနေသော Stop Loss များ ဖြစ်သည်။ Sell ဝင်ထားသူများ၏ Buy Stop Orders များ ဖြစ်သည်။ စျေးနှုန်းသည် ဤအမှတ်များကို ကျော်တက်သွားပါက BSL ကို ရယူသည် (Sweep လုပ်သည်) ဟု ခေါ်သည်။ Smart Money သည် ဤနေရာတွင် မိမိ၏ Sell Order များကို ဖြည့်တင်းနိုင်ရန် BSL ကို ရှာဖွေသည် [4]။
*   **Sell Side Liquidity (SSL)**: ဤသည်မှာ စျေးကွက်၏ အောက်ပိုင်း (Swing Lows, Support Levels, Equal Lows) များတွင် ရှိနေသော Stop Loss များ ဖြစ်သည်။ Buy ဝင်ထားသူများ၏ Sell Stop Orders များ ဖြစ်သည်။ စျေးနှုန်းသည် ဤအမှတ်များကို ကျိုးဆင်းသွားပါက SSL ကို ရယူသည်ဟု ခေါ်သည်။ Smart Money သည် ဤနေရာတွင် မိမိ၏ Buy Order များကို ဖြည့်တင်းနိုင်ရန် SSL ကို ရှာဖွေသည် [4]။

| အမျိုးအစား | တည်နေရာ | ပါဝင်သော Orders များ | Smart Money ၏ ရည်ရွယ်ချက် | Sweep ပြီးနောက် ဖြစ်နိုင်ခြေ |
| :--- | :--- | :--- | :--- | :--- |
| **BSL Sweep** | Swing Highs / Resistance | Buy Stops (Short Sellers' SL) | Sell Orders များ ဖြည့်ရန် ဝယ်လိုအား ရှာခြင်း | Bearish Reversal (ကျဆင်းမည်) |
| **SSL Sweep** | Swing Lows / Support | Sell Stops (Long Buyers' SL) | Buy Orders များ ဖြည့်ရန် ရောင်းလိုအား ရှာခြင်း | Bullish Reversal (တက်မည်) |

### ၂.၂ Internal Range Liquidity (IRL) နှင့် External Range Liquidity (ERL)

ICT (Inner Circle Trader) ၏ အယူအဆအရ စျေးကွက်၏ Structure ပေါ်မူတည်၍ Liquidity ကို Internal နှင့် External ဟူ၍ ထပ်မံ ခွဲခြားနိုင်သည် [5]။

*   **External Range Liquidity (ERL)**: အဓိက Swing High နှင့် Swing Low များတွင် ရှိသော Liquidity ဖြစ်သည်။ ဤနေရာများသည် Trend ပြောင်းလဲမှု သို့မဟုတ် ကြီးမားသော Reversal များ ဖြစ်ပေါ်နိုင်သည့် နေရာများ ဖြစ်သည်။ ERL သည် အဖွဲ့အစည်းကြီးများအတွက် အဓိက ပစ်မှတ် (Magnet) ဖြစ်သည်။ စျေးနှုန်းသည် ERL ကို ရယူပြီးမှသာ အခြားဘက်သို့ လှည့်ပြန်ရန် ပြင်ဆင်သည် [5]။
*   **Internal Range Liquidity (IRL)**: အဓိက Range အတွင်း ဖြစ်ပေါ်နေသော Pullback များ၊ Minor Highs/Lows များတွင် ရှိသော Liquidity ဖြစ်သည်။ အထူးသဖြင့် Range အတွင်းရှိ Fair Value Gaps (FVGs) များသည် IRL အဖြစ် သတ်မှတ်သည်။ စျေးနှုန်းသည် ERL ကို ရယူပြီးနောက် IRL (FVG) ကို ဖြည့်တင်းရန် ပြန်လည် ဆွဲယူလာတတ်သည် [5]။

စျေးကွက်၏ သဘာဝအလျောက် လှုပ်ရှားမှုသည် ERL ကိုရယူခြင်းနှင့် IRL ကို ဖြည့်တင်းခြင်းတို့ကို အလှည့်ကျ ပြုလုပ်နေခြင်း ဖြစ်သည်။ ထို့ကြောင့် စျေးကွက်သည် ERL တစ်ခုကို Sweep လုပ်ပြီးပါက IRL ဆီသို့ ပြန်သွားမည်ဖြစ်ပြီး၊ IRL ကို ဖြည့်တင်းပြီးပါက ERL ဆီသို့ ဦးတည်မည်ဖြစ်သည်။

---

## အပိုင်း (၃) - Liquidity Sweep နှင့် Break of Structure (BOS) ကွဲပြားချက်များ

Trading လုပ်ရာတွင် များသောအားဖြင့် စျေးနှုန်းသည် အရေးကြီးသော Level တစ်ခုကို ကျော်သွားသောအခါ ထို Level သည် Break of Structure (BOS) ဖြစ်သည် (Trend ဆက်သွားမည်) ဟုတ်သလား၊ သို့မဟုတ် Liquidity Sweep ဖြစ်သည် (ပြန်လှည့်မည်) ဟုတ်သလား ခွဲခြားရန် ခက်ခဲတတ်သည်။

### ၃.၁ Liquidity Sweep ၏ လက္ခဏာရပ်များ

Liquidity Sweep တစ်ခုကို အတည်ပြုရန် အောက်ပါ လက္ခဏာရပ်များကို ကြည့်ရှုရမည် [6] [7]:

1.  **Candlestick Body vs Wick**: BOS သည် Body Close ဖြင့် ကျော်သွားခြင်း ဖြစ်ပြီး Trend ဆက်သွားမည်ဟု ဆိုလိုသည်။ Sweep သည် Wick ဖြင့်သာ ကျော်ပြီး ပြန်လှည့်လာခြင်း ဖြစ်ပြီး Reversal ဖြစ်နိုင်ခြေ များသည်။ စျေးနှုန်းသည် Level ကို ကျော်သွားသော်လည်း ထို Candle သို့မဟုတ် နောက် Candle များတွင် ပြန်လည် ပိတ်သွားပါက (Close back inside the range) ၎င်းကို Sweep ဟု ခေါ်သည် [7]။
2.  **Volume ကွဲပြားခြင်း**: Stop Hunt (Sweep) ဖြစ်သောအခါ Volume သည် ရုတ်တရက် မြင့်တက်လာပြီးနောက် ချက်ချင်း ပြန်ကျသွားတတ်သည် (Spike and fade)။ အမှန်တကယ် Breakout (BOS) ဖြစ်ပါက Volume သည် ဆက်လက် မြင့်တက်နေပြီး စျေးနှုန်းသည် အရှိန်အဟုန် (Momentum) ဖြင့် ဆက်သွားမည်ဖြစ်သည် [7]။
3.  **Timeframe အပေါ် မူတည်ခြင်း**: Stop Hunts များသည် များသောအားဖြင့် Lower Timeframes (1m, 5m, 15m) တွင် တွေ့ရလေ့ရှိသည်။ Liquidity Sweeps များသည် Higher Timeframes (1H, 4H, Daily) တွင် ပိုမို ခိုင်မာသော Signal ကို ပေးစွမ်းနိုင်သည် [7]။
4.  **Follow-through (ဆက်သွားမှု)**: အမှန်တကယ် BOS ဖြစ်ပါက စျေးနှုန်းသည် ထို Level အောက်/အပေါ်တွင် အခြေချပြီး ဆက်သွားမည်။ Sweep ဖြစ်ပါက ချက်ချင်း (သို့မဟုတ် အနည်းငယ် Consolidate ပြီးနောက်) ပြန်လှည့်မည် [7]။

### ၃.၂ Stop Hunt နှင့် Inducement ကွဲပြားချက်များ

Liquidity Sweep ကို Stop Hunt ဟုလည်း ခေါ်ဆိုသော်လည်း၊ Smart Money ၏ ရည်ရွယ်ချက်အရ ၎င်းတို့သည် အနည်းငယ် ကွဲပြားနိုင်သည် [8]။

*   **Inducement (အစာကျွေးခြင်း)**: စျေးနှုန်းသည် အဓိက Order Block (OB) သို့ မရောက်မီ၊ လမ်းခုလတ်တွင် Retail Trader များအား Trade ဝင်ရန် ဆွဲဆောင်ခြင်း (Bait ကျွေးခြင်း) ဖြစ်သည်။ ၎င်းသည် Liquidity Pool တစ်ခုကို ဖန်တီးရန် ရည်ရွယ်သည်။ ထို Inducement ကို ရယူပြီးမှသာ အစစ်အမှန် OB သို့ သွားလေ့ရှိသည် [8]။
*   **Stop Hunt / Liquidity Sweep**: ၎င်းသည် မူလကတည်းက ရှိနေပြီးသား အရေးကြီးသော Level (Swing High/Low) ကို ရုတ်တရက် ရုတ်သိမ်းခြင်း ဖြစ်သည်။ အဖွဲ့အစည်းကြီးများ၏ Order ကြီးများကို ဖြည့်တင်းရန် တိုက်ရိုက် ပစ်မှတ်ထားသော လှုပ်ရှားမှု ဖြစ်သည် [8]။

သိရှိထားရမည်မှာ Inducement သည် Sweep မတိုင်မီ ဖြစ်ပေါ်လေ့ရှိပြီး၊ အမှန်တကယ် Trade ဝင်ရမည့် နေရာကို မြှင့်တင်ပေးသော အခန်းကဏ္ဍတွင် ရှိသည်။

---

## အပိုင်း (၄) - အချိန်ကာလအလိုက် Liquidity Sweep များ (Session-Based Sweeps)

စျေးကွက်၏ အချိန်ဇယားသည် Liquidity Sweep ဖြစ်ပေါ်မှုတွင် အလွန်အရေးပါသည်။ အဖွဲ့အစည်းကြီးများသည် အချိန်အပိုင်းအခြားအလိုက် စျေးကွက်ကို ထိန်းချုပ်လေ့ရှိသောကြောင့် Session-Based Sweeps များသည် အလွန် ထိရောက်သော နည်းဗျူဟာတစ်ခု ဖြစ်သည် [9]။

### ၄.၁ Asian Range Liquidity

Asian Session (တိုကျို) သည် များသောအားဖြင့် Volatility နည်းပြီး ဘေးတိုက် (Range) သွားလေ့ရှိသည်။ Asian Session ၏ အမြင့်ဆုံး (Asian High) နှင့် အနိမ့်ဆုံး (Asian Low) တို့သည် London နှင့် New York Session များအတွက် အဓိက Liquidity Target များ ဖြစ်လာသည်။ London Session စတင်ချိန်တွင် Asian Range ၏ တစ်ဖက်ကို Sweep လုပ်ပြီးမှ အခြားတစ်ဖက်သို့ ပြင်းထန်စွာ ရွေ့လျားလေ့ရှိသည် [9]။

### ၄.၂ London Open (Judas Swing) Sweep

Judas Swing ဆိုသည်မှာ London Open တွင် ဖြစ်ပေါ်လေ့ရှိသော လှည့်ဖြားသည့် လှုပ်ရှားမှု ဖြစ်သည် [10]။
*   **ဥပမာ**: ထိုနေ့၏ Trend မှာ အတက် (Bullish) ဖြစ်မည်ဆိုပါက၊ London Open တွင် စျေးနှုန်းသည် အောက်သို့ အရင်ကျပြပြီး Asian Low ကို Sweep လုပ်သည်။ Retail များက Downtrend ဟု ထင်ပြီး Sell ကြချိန်တွင် Smart Money များက ဝယ်ယူပြီး စျေးကို အပေါ်သို့ တင်လိုက်ကြသည်။
*   **တကယ်တမ်း**: ထို Session ၏ Open ပြီးစ၊ စျေးနှုန်းသည် Range အောက်သို့ ရုတ်တရက် ကျဆင်းသွားပြီး Stop Loss များကို ရုတ်သိမ်းကာ ပြန်တက်လာခြင်းဖြစ်သည်။ ထို့ကြောင့် London Open တွင် ရုတ်တရက် ရွေ့လျားမှုများကို ချက်ချင်း Trade မဝင်သင့်ဘဲ Liquidity Sweep ဖြစ်နိုင်ခြေကို သတိပြုသင့်သည်။

### ၄.၃ New York Session Sweep

New York Session သည် London Session ၏ Liquidity ကို ပြန်လည် ရယူလေ့ရှိသည်။ အထူးသဖြင့် London High သို့မဟုတ် London Low ကို Sweep လုပ်ပြီး Reversal ဖြစ်ခြင်း သို့မဟုတ် Trend ဆက်လက်သွားခြင်းများ ဖြစ်ပေါ်တတ်သည်။ London Session တွင် ဆွဲယူမရသေးသော Liquidity ကို New York Session တွင် ဆက်လက် ဆွဲယူတတ်သည် [9]။

---

## အပိုင်း (၅) - PO3 (Power of 3) နှင့် Manipulation Cycle (AMD Model)

Smart Money ၏ နေ့စဉ် လှုပ်ရှားမှုကို PO3 (Power of 3) သို့မဟုတ် AMD (Accumulation, Manipulation, Distribution) Model ဖြင့် ရှင်းပြနိုင်သည်။ Liquidity Sweep သည် ဤ Model ၏ အဓိက အဆင့်တစ်ခု ဖြစ်သည် [10] [11]။

### ၅.၁ Accumulation (စုဆောင်းခြင်း)

Asian Session အတွင်း စျေးနှုန်းကို Range တစ်ခုအတွင်း ထိန်းထားပြီး Order များ စုဆောင်းခြင်း။ ဤအဆင့်တွင် Volatility အလွန်နည်းပြီး စျေးနှုန်းသည် Range ၏ အထက်နှင့် အောက်တွင် Stop Loss များ စုဝေးလာစေသည်။

### ၅.၂ Manipulation (Liquidity Sweep အဆင့်)

London Open တွင် စျေးနှုန်းကို Trend နှင့် ဆန့်ကျင်ဘက်သို့ တွန်းပို့ပြီး Liquidity ရယူခြင်း (Stop Hunt)။ ဥပမာအားဖြင့် Bullish နေ့တွင် စျေးကွက်သည် Range အောက်သို့ ရုတ်တရက်ကျပြီး Sell Side Liquidity ကို Sweep လုပ်သည်။ ထိုအခါ Retail Trader များသည် Bearish ဖြစ်သွားပြီဟု ထင်မြင်ပြီး Sell ပို့ကြသည်။ သို့သော် Smart Money သည် ထို Sell Orders များကို ပြင်းထန်စွာ ဝယ်ယူသည်။

### ၅.၃ Distribution (ဖြန့်ဝေခြင်း)

Manipulation ပြီးနောက် အစစ်အမှန် Trend အတိုင်း စျေးနှုန်းကို ပြင်းထန်စွာ ရွေ့လျားစေပြီး အကျိုးအမြတ် ယူခြင်း။ စျေးနှုန်းသည် Manipulation ၏ ဆန့်ကျင်ဘက် (Range အပေါ်) သို့ ရုတ်တရက် ရွေ့လျားသွားသည်။

**Trading Tip**: သင်သည် Accumulation အဆင့်ကို မြင်ပါက၊ Manipulation ကို စောင့်ပါ။ Manipulation (Sweep) ဖြစ်ပြီးမှ Distribution အတိုင်း လိုက်ပါ Trade ဝင်ပါ။

---

## အပိုင်း (၆) - အဆင့်မြင့် Liquidity Sweep Strategies (Entry Models)

Liquidity Sweep ကို တွေ့ရှိပါက Trade ချက်ချင်း မဝင်သင့်ဘဲ Confirmation များ ရှာဖွေရမည်။

### ၆.၁ Order Block (OB) နှင့် Fair Value Gap (FVG) ပေါင်းစပ်ခြင်း

Liquidity Sweep ပြီးနောက် စျေးနှုန်းသည် လျင်မြန်စွာ ပြောင်းလဲသွားပါက (Displacement)၊ ထိုရွေ့လျားမှုအတွင်းတွင် Fair Value Gap (FVG) ဖြစ်ပေါ်လာတတ်သည်။ ထို့ပြင် Sweep မတိုင်မီ ပြောင်းလဲခဲ့သော နောက်ဆုံး Candle ကို Order Block (OB) အဖြစ် သတ်မှတ်နိုင်သည်။
*   **Strategy**: Sweep ပြီးနောက် စျေးနှုန်းသည် ဖြစ်ပေါ်လာသော FVG သို့မဟုတ် OB ထဲသို့ ပြန်ရောက်လာပါက (Return to OB) Entry ဝင်ရန် အကောင်းဆုံး အချိန်ဖြစ်သည် [12]။
*   **Stop Loss**: Sweep လုပ်ခဲ့သော Wick ၏ အပြင်ဘက်တွင် ထားပါ။
*   **Take Profit**: ဆန့်ကျင်ဘက် Liquidity Zone (EQH/EQL, Swing High/Low) တွင် ထားပါ။

### ၆.၂ Lower Timeframe (LTF) Confirmation

Higher Timeframe (HTF) တွင် Sweep ဖြစ်ပြီးပါက Lower Timeframe (M5, M15) သို့ဆင်း၍ အတည်ပြုချက် ရှာပါ။
*   **Change of Character (CHoCH)**: M15 တွင် Trend လေးပြောင်းသွားသည့် (Mini CHoCH) ကိုစောင့်ပြီး entry ဝင်ပါ။
*   **Candlestick Rejection**: OB ဇုန်မှ ထင်ရှားသော Pin Bar, Engulfing candle ထွက်လာခြင်း [13]။

### ၆.၃ SMT Divergence နှင့် ဆက်စပ်မှု

SMT (Smart Money Technique) သည် ဆက်စပ်နေသော Asset နှစ်ခု (ဥပမာ - EURUSD နှင့် GBPUSD) အကြား ကွာဟချက်ကို ကြည့်ရှုခြင်း ဖြစ်သည် [14]။
*   အကယ်၍ EURUSD က High အသစ်တစ်ခု ပြုလုပ်နိုင်သော်လည်း၊ GBPUSD က မပြုလုပ်နိုင်ပါက ၎င်းကို SMT Divergence ဟု ခေါ်သည်။
*   ၎င်းသည် တစ်ဖက်တွင် Liquidity Sweep ဖြစ်သွားပြီး စျေးကွက် ပြောင်းလဲတော့မည်ကို ကြိုတင် အချက်ပြခြင်း ဖြစ်သည်။ အလားတူ Index များ (SPX, NDX, DJI) အကြားတွင်လည်း SMT Divergence ကို အသုံးပြုနိုင်သည်။

---

## အပိုင်း (၇) - Risk Management နှင့် စိတ်ပညာ (Psychology in Liquidity Sweeps)

Liquidity Sweep Trading တွင် အကြီးမားဆုံး စိန်ခေါ်မှုမှာ **"စိတ်ရှည်မှု (Patience)"** ဖြစ်သည်။

*   **FOMO ရှောင်ကြဉ်ခြင်း**: စျေးနှုန်းက Liquidity ကို မယူသေးဘဲ သွားနေပါက လိုက်မဝင်ပါနှင့်။ စျေးကွက်သည် အမြဲတမ်း ပြန်လာပြီး Liquidity ယူလေ့ရှိသည်။
*   **Stop Loss Placement**: SMC Trader များသည် Stop Loss ကို အလွန် တင်းကျပ်စွာ ထားတတ်ကြသည်။ သို့သော် Liquidity Sweep များသည် SL ကို ထိသွားနိုင်သဖြင့် SL ကို အနည်းငယ် ချောင်ချောင်ထားရန် (Buffer ပေးရန်) လိုအပ်သည်။ Sweep လုပ်ခဲ့သော Wick ၏ အပြင်ဘက် Pip အနည်းငယ်အကွာတွင် SL ထားခြင်းသည် လုံခြုံမှုရှိသည် [15]။
*   **Risk to Reward (RR)**: Liquidity ကို အခြေခံသော Trade များသည် များသောအားဖြင့် 1:3 မှ 1:10 အထိ မြင့်မားသော RR ကို ပေးစွမ်းနိုင်သည်။
*   **Context & Confluence**: D1 Trend ပေါ်တက်၊ H4 OB ထဲရောက်၊ M15 FVG ထပ်ဖြည့် → အဲ့လို Timeframe ၃ခုလုံး ညှိယူတာမျိုးကို စက်ထက် လူက ပိုမြင်လွယ်ပါတယ်။ News (သတင်းကြီး) ထွက်ခါနီး Trade ဝင်တာမျိုးကို ရှောင်ဖို့ လူကိုယ်တိုင် Economic Calendar စစ်ရပါမယ်။

## အပိုင်း (၈) - နိဂုံး (Conclusion)

Smart Money Concept တွင် Liquidity Sweep ကို နားလည်ခြင်းသည် မျက်စိဖွင့်ပေးလိုက်သကဲ့သို့ ဖြစ်သည်။ စျေးကွက်ကို Retail မျက်စိဖြင့် ကြည့်မည့်အစား အဖွဲ့အစည်းကြီးများ၏ အမြင်ဖြင့် ကြည့်တတ်လာမည် ဖြစ်သည်။ 

Liquidity Sweep သည် စျေးကွက်၏ လှည့်ဖြားခြင်း (Manipulation) အဆင့်ဖြစ်ပြီး၊ ထို့နောက် အစစ်အမှန် ရွေ့လျားမှု (Distribution) ကို ဦးတည်သည်။ Break of Structure (BOS) နှင့် Sweep ကို ခွဲခြားနိုင်ခြင်း၊ Internal နှင့် External Liquidity များကို သိရှိခြင်း၊ နှင့် Session-Based Sweeps များကို အချိန်မှီ ပြင်ဆင်နိုင်ခြင်းတို့သည် အောင်မြင်သော SMC Trader တစ်ယောက်ဖြစ်ရန် မရှိမဖြစ် လိုအပ်ချက်များ ဖြစ်သည်။

သတိပြုရမည့်အချက်မှာ Liquidity Sweep သည် စျေးကွက်အား အမြဲတမ်း ပြန်လှည့်စေသည်ဟု မဆိုလိုပါ။ အကယ်၍ Sweep ပြီးနောက် စျေးနှုန်းသည် ထို Level ကို ထပ်မံ ကျော်သွားပါက ၎င်းသည် Breakout (BOS) ဖြစ်သွားနိုင်သည်။ ထို့ကြောင့် Sweep ကို ဖြစ်နိုင်ခြေ (Context) အဖြစ်သာ ယူဆပြီး၊ Lower Timeframe (LTF) ၏ Confirmation (CHoCH, FVG, OB) များကို အသုံးပြု၍ Trade ဝင်ခြင်းသည် အကောင်းဆုံးဖြစ်သည်။

ဤသုတေသနစာတမ်းတွင် ဖော်ပြထားသော Concept များကို လက်တွေ့ Chart ပေါ်တွင် အကြိမ်ကြိမ် Backtest လုပ်ပြီး ကိုယ်ပိုင် အတွေ့အကြုံ ရယူရန် တိုက်တွန်းလိုပါသည်။

## ကိုးကားစာရင်း (References)

[1] ThinkMarkets. "Liquidity Sweep Trading: What It Is and How to Trade It." https://www.thinkmarkets.com/en/trading-academy/forex/liquidity-sweep-trading-smart-money-guide/
[2] Manus AI Project Instructions - SMC
[3] Zeiierman. "Liquidity Sweeps vs Stop Hunts: Key Differences Explained." https://www.zeiierman.com/blog/liquidity-sweeps-vs-stop-hunts/
[4] FluxCharts. "Liquidity Sweeps Explained: How to Identify and Trade Them." https://www.fluxcharts.com/articles/liquidity-sweeps-explained-how-to-identify-and-trade-them
[5] InnerCircleTrader. "ICT Internal & External Range Liquidity (IRL & ERL) — Complete Guide + Free PDF." https://innercircletrader.net/tutorials/ict-internal-external-liquidity/
[6] LuxAlgo. "Liquidity Sweep." https://www.luxalgo.com/blog/what-are-liquidity-sweeps-in-trading/
[7] Zeiierman. "Liquidity Sweeps vs Stop Hunts: Key Differences Explained." https://www.zeiierman.com/blog/liquidity-sweeps-vs-stop-hunts/
[8] FXNX. "Inducement vs Sweep vs Stop Hunt: Smart Money's Intent." https://fxnx.com/en/blog/inducement-vs-sweep-vs-stop-hunt-smart-money-s-intent
[9] ThinkMarkets. "Liquidity Sweep Trading: What It Is and How to Trade It." https://www.thinkmarkets.com/en/trading-academy/forex/liquidity-sweep-trading-smart-money-guide/
[10] InnerCircleTrader. "ICT Power of 3 — Accumulation, Manipulation, Distribution Explained (Free PDF)." https://innercircletrader.net/tutorials/ict-power-of-3/
[11] FXOpen. "ICT Power of 3 (PO3) Explained." https://fxopen.com/blog/en/what-is-ict-po3-and-how-do-traders-use-it/
[12] AlchemyMarkets. "Liquidity Sweep Explained with Examples." https://alchemymarkets.com/education/strategies/liquidity-sweep/
[13] VasilyTrader. "Best Liquidity Grab / Sweep Strategy For Trading Forex (Smart Money Concept SMC)." https://www.vasilytrader.com/post/best-liquidity-grab-sweep-forex-trading-strategy-smc
[14] Manus AI Project Instructions - SMC (Smart Money Concept (SMC) Liquidity Zone: အသေးစိတ် သုတေသနစာတမ်း)
[15] Trading Strategy Guides. "Day 17: Risk Management In ICT & SMC Trading — Position Sizing, Stop Loss & Drawdown." https://tradingstrategyguides.com/day-17-risk-management-in-ict-smc-trading-position-sizing-stop-loss-drawdown/
