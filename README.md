# JERA MODA - Zoho Creator Widgets

Custom dashboard widgets for Zoho Creator, hosted on GitHub Pages.

## Setup
1. Create a GitHub repo named `zoho-widgets`
2. Enable GitHub Pages (Settings → Pages → Source: main branch)
3. Push these files to the repo
4. Register each widget in Zoho Creator → Settings → Widgets → New Widget → External

## Widgets
| Widget | File | Description |
|--------|------|-------------|
| Overview | `overview.html` | 전체현황 - KPI summary dashboard |
| Stock View | `stock-view.html` | 재고현황 - Inventory by category |
| Offer View | `offer-view.html` | 오퍼현황 - Buyer offers & allocations |
| Sales View | `sales-view.html` | 매출현황 - Sales by customer/month |

## Versioning
Append `?v=N` to URLs when registering in Creator to bust cache after updates.

## Data Source
Widgets use `ZOHO.CREATOR.API` to fetch data from Creator forms.
For Inventory data, widgets call Zoho Inventory API via `ZOHO.CREATOR.UTIL.invokeURL()`.
