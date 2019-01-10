# Waves + Current
@size[50%](Waves don't die. Let me crash here for the moment)

---

@snap[east]
```json
{
  "eventType": "checkingBalanceUpdate",
  "brazeType": "attribute",
  "brazeConfig": {
    "paths": [
      {
        "key": "bank_debit_balance",
        "path": "data/availableBalance"
      },
      {
        "key": "bank_debit_balance_as_of_date_time",
        "path": "data/availableBalanceAsOfDateTime"
      }
    ]
  }
}
```
@snapend

@snap[west]
```json
{
  "id": "0dfdb3d3-0ce2-47f4-899e-9a01cd52c9a1",
  "data": {
    "accountUUID": "988b9b4d-6f6e-45a8-bcf4-7fc1192603a0",
    "ledgerBalance": 129.9,
    "availableBalance": 37.36,
    "ledgerBalanceAsOfDateTime": "2018-12-18T03:00:00.000Z",
    "availableBalanceAsOfDateTime": "2018-12-20T01:51:43.713Z"
  },
  "type": "checkingBalanceUpdate",
  "userUUID": "98d325d5-307f-433f-be33-65f05d04783e",
  "publishedAt": "2018-12-20T01:51:45.539Z"
}
```
@snapend

---?image=assets/gifs/charlie.gif
---?image=assets/gifs/ballmer.gif
---?image=assets/gifs/charlie.gif
---?image=assets/gifs/ballmer.gif
---

## Darion Miller or John Denver?
<img src="assets/jd_darion/jd_darion.jpg" style="height: 50%; width: 50%; border: 0; box-shadow: none !important; background: none !important;"/>
---

## DM or JD?
<img src="assets/jd_darion/darion_1.png" style="height: 40%; width: 40%; border: 0; box-shadow: none !important; background: none !important;"/>
---

@snap[west]
<img src="assets/jd_darion/darion_1.png" style="height: 40%; width: 40%; border: 0; box-shadow: none !important; background: none !important;"/>
@snapend

@snap[east]
@size[1.5em](Darion Miller)
@snapend
---

## DM or JD?
<img src="assets/jd_darion/jd_1.png" style="height: 40%; width: 40%; border: 0; box-shadow: none !important; background: none !important;"/>
---

@snap[west]
<img src="assets/jd_darion/jd_1.png" style="height: 75%; width: 75%; border: 0; box-shadow: none !important; background: none !important;"/>
@snapend

@snap[east]
@size[1.5em](Darion Miller)
@snapend
---

## DM or JD?
<img src="assets/jd_darion/darion_2.png" style="height: 40%; width: 40%; border: 0; box-shadow: none !important; background: none !important;"/>
---

@snap[west]
<img src="assets/jd_darion/darion_2.png" style="height: 100%; width: 100%; border: 0; box-shadow: none !important; background: none !important;"/>
@snapend

@snap[east]
@size[1.5em](Darion Miller)
@snapend
---

## Agenda

* Data

* Bank platform

---?image=assets/gifs/charlie.gif
---

## Data
---

<img src="assets/core_values.png" style="height: 100%; width: 100%;"/>
---

<img src="assets/data_driven.png" style="height: 100%; width: 100%;"/>
---

<img src="assets/friends/pramod.png" style="height: 40%; width: 40%;"/>
---

<img src="assets/platform_architecture_1.png" style="height: 65%; width: 65%;"/>
---

## Data LAKE
<img src="assets/data_lake.png" style="height: 75%; width: 75%;"/>
---

### ITS A LAKE... OF Data
<img src="assets/data_lake.png" style="height: 50%; width: 50%; border: 0; box-shadow: none !important; background: none !important;"/>

@ul
- @size[65%](centralizes all of our data)
- @size[65%](mixpanel, braze, plaid, green dot, backend events)
- @size[65%](use case driven views)
@ulend

---?image=assets/gifs/ballmer.gif
---

## DM or JD?
<img src="assets/jd_darion/jd_2.png" style="height: 40%; width: 40%; border: 0; box-shadow: none !important; background: none !important;"/>
---

@snap[west]
<img src="assets/jd_darion/jd_2.png" style="height: 100%; width: 100%; border: 0; box-shadow: none !important; background: none !important;"/>
@snapend

@snap[east]
@size[1.5em](John Denver)
@snapend
---

## DM or JD?
<img src="assets/jd_darion/darion_4.png" style="height: 40%; width: 40%; border: 0; box-shadow: none !important; background: none !important;"/>
---

@snap[west]
<img src="assets/jd_darion/darion_4.png" style="height: 40%; width: 40%; border: 0; box-shadow: none !important; background: none !important;"/>
@snapend

@snap[east]
@size[1.5em](John Denver)
@snapend

---?image=assets/gifs/charlie.gif
---

## Bank Platform

@ul
- Green Dot ✅
- We're not really the source of truth for anything
- API Calls + Events
@ulend
---

### Service View
<img src="assets/checking/checking_overview.png" style="height: 100%; width: 100%;"/>
---

### Webhooks
<img src="assets/checking/webhooks.png" style="height: 52%; width: 52%;"/>
---

<img src="assets/checking/checking_0.png" style="height: 75%; width: 75%;"/>
---

<img src="assets/platform_architecture_3.png" style="height: 100%; width: 100%;"/>
---

<img src="assets/checking/platform_architecture_6.png" style="height: 100%; width: 100%;"/>
---
<img src="assets/checking/platform_architecture_7.png" style="height: 100%; width: 100%;"/>
---
<img src="assets/checking/platform_architecture_8.png" style="height: 100%; width: 100%;"/>
---
<img src="assets/checking/platform_architecture_10.png" style="height: 100%; width: 100%;"/>
---
<img src="assets/opt_in_out.png" style="height: 100%; width: 100%;"/>

---?image=assets/gifs/ballmer.gif
---

## DM or JD?
<img src="assets/jd_darion/darion_3.png" style="height: 40%; width: 40%; border: 0; box-shadow: none !important; background: none !important;"/>
---

@snap[west]
<img src="assets/jd_darion/darion_3.png" style="height: 100%; width: 100%; border: 0; box-shadow: none !important; background: none !important;"/>
@snapend

@snap[east]
@size[1.5em](Darion Miller)
@snapend
---

## DM or JD?
<img src="assets/jd_darion/jd_3.png" style="height: 40%; width: 40%; border: 0; box-shadow: none !important; background: none !important;"/>
---

@snap[west]
<img src="assets/jd_darion/jd_3.png" style="height: 90%; width: 90%; border: 0; box-shadow: none !important; background: none !important;"/>
@snapend

@snap[east]
@size[1.5em](Darion Miller)
@snapend
---

## Questions

😬
