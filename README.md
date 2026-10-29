# QuietPlate

QuietPlate is a Chrome extension for people living with or recovering from an eating disorder or disordered eating. It hides calorie numbers on restaurant and menu websites, so you can choose what you actually want to eat instead of what a number tells you to.

<img width="278" height="282" alt="image" src="https://github.com/user-attachments/assets/1de9b574-28c2-47be-851e-0307882f92d8" />


## Why

Calorie counts now appear next to almost every item on chain restaurant menus. For many people they're neutral information. For someone with an eating disorder, they can be a trigger. A single number can turn ordering into counting and comparing, and it can steer you away from the meal you wanted, or any meal at all. Recovery often means learning to eat by hunger, craving, and enjoyment again, and that's hard when every option is labeled with a number.

QuietPlate takes the numbers off the page so the menu is just food again.

## What it does

QuietPlate scans the page you're viewing and hides calorie numbers, including ones split across separate elements, as on many chain restaurant sites. It keeps working as the page loads new content. All scanning happens locally in your browser, and page content is never sent anywhere.

- One-click toggle to turn the filter on or off from the popup
- Light and dark themes, matching your browser preference by default
- A report button for flagging a page where a calorie number slipped through or the filter didn't run — opens a pre-filled form with the page URL, nothing is sent unless you click it

## Installing

QuietPlate isn't published on the Chrome Web Store yet. Until then, you can load it as an unpacked extension:

1. Clone or download this repository
2. Open `chrome://extensions` in Chrome
3. Turn on "Developer mode" (top right)
4. Click "Load unpacked" and select this repository's folder

## Privacy

QuietPlate only stores your on/off and theme preferences on your device. See [PRIVACY.md](PRIVACY.md) for the full policy, including what the report feature sends and to whom.

## Testing

```
npm install
npm test
```
