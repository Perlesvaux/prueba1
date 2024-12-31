# NarrowD documentation

## The main feature:

You can create a list of sites with the

<button type="button" title="Create new list" style="display: inline-flex; align-items: center; border: 1px solid red; background-color: yellow;">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 -960 960 960" width="24px" height="24px" fill="red"><path d="M154-406v-52h288v52H154Zm0-150v-52h432v52H154Zm0-150v-52h432v52H154Zm492 456v-156H490v-52h156v-156h52v156h156v52H698v156h-52Z" /></svg>
</button>

You can add the site you're currently seeing to the extension's list, and after that, doing a search in the extension's search bar will command your browser's default search engine to look (preferably) for results matching exactly what you wrote, and only in the sites you listed in the extension. For example:

If you add "developer.chrome.com" and "developer.mozilla.org" to the extension's list, when you search "manifest" in the extension's search bar, you will get results only from those sites, meaning your results will be about the browser extension file that must be named "manifest.json" (which is likely what you want), and not about the definition of "manifest" nor about any movie, song or literary work named "manifest".

The example above shows how the extension might allow you to write less. How so? Because when you're searching a technical term that looks like a normal word (like "manifest"), you have to provide extra context for the search engine to understand what you're looking for (writing "extension manifest json" instead of just "manifest", for example), but the extension allows you to narrow down that context to a closed site list beforehand.

I think the extension might be useful for people who have a favorite set of sites to look for documentation, tutorials, articles or general information, and don't want to see results from anywhere else, nor want to be so specific every time they need to dissipate the engine's confusion with some queries (confusion that often doesn't happen when it knows where to look).

By the way, if the site you're currently seeing is already in your list, the action icon will become green.

Also, every listed site gets a checkbox (that is ticked by default) that you can untick to exclude that site from your next search without having to remove it from the list, and the extension will remember which checkboxes were left ticked and which were left unticked when you re-activate the action's popup.

I've tested the extension with Google, Bing, DuckDuckGo and Yahoo, and the results enforced by the extension are consistently very similar.
