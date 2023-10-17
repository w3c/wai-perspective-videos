[![Netlify Status](https://api.netlify.com/api/v1/badges/db4f7d10-6157-49c7-89b8-3b6573fbe49d/deploy-status)](https://app.netlify.com/sites/wai-perspective-videos/deploys)

Formerly at https://www.w3.org/WAI/perspectives/

## Translation Notes

### Changelog/Acknowledgements

Do not translate `changelog.md` and `acknowledgements.md`.

### Links with images in index page

In `index.[lang].md`: add the language shortcode of your translation at the end of the URLs listed in "Perspectives Videos"

Example (French translation):
```markdown
- [![](img/thumbnails/keyboard.jpg)<br>Compatibilité avec le clavier]({{ "/perspective-videos/keyboard/fr" | relative_url }})
```

### Subtitles & descriptions

- WebVTT files are located in `_perspective-videos/cc/`.
- Language subfolders are used: they gather all the WebVTT files of this resource in a specific language.

1. In `_perspective-videos/cc/`, create a new folder named after the language shortcode of your translation (example: `zh-hans/`).\
Alternatively, you can duplicate the `en/` folder, then rename it.
2. Add the translated WebVTT files in this new folder. 
3. Use the language shortcode of your translation at the end of the basename, instead of `.en` used by the original files.\
Example: `keyboard_ad_desc.zh-hans.vtt` &mdash; Simplified Chinese translation of `keyboard_ad_desc.en.vtt`
4. Edit `vtt.yml`located in `_data/wai-perspective-videos/`: add your language shortcode in the list of available languages for the WebVTT file(s) you have translated.\
   Example consistent with step 3 &mdash; description of the audio-described version of the `keyboard` video translated into Simplified Chinese:
   - Add a new line containing `- zh-hans` to the `descriptions-ad` list, in the `name: keyboard` section.
   - Make sure to use proper indentation.
    
    ```yaml
    - name: keyboard
      captions:
        - en
      captions-ad:
        - en
      subtitles:
        - fr
      subtitles-ad:
        - fr
      descriptions:
        - en
        - fr
      descriptions-ad:
        - en
        - fr
        - zh-hans
    ```