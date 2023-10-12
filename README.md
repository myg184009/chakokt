-- import: fastn-community.github.io/bling/quote

;; `page` is the container type component in `doc-site`. All other components of
;; doc-site can be used inside `page` component.
;; The container type component needs an `end` statement to mark the end of this
;; container component.

;; Page title goes in the caption area.
;; Also, you can give the `site-name` of your site as header property

;; ========================= REMOVE THE COMMENT BELOW ==========================
-- ds.page:New title of this page
site-name: My Site
;; ================================= END =======================================

-- quote.background-image: Lucius Annaeus Seneca
quote-background: https://e0.pxfuel.com/wallpapers/491/601/desktop-wallpaper-ultra-original-and-background-it-ultra.jpg
text-color: #FFF

As long as you live, keep learning how to live.


;; By placing `end` marker after the `quote.chalice` component, the
;; `quote.chalice` would become child of the `ds.page`.

;; This is the end marker for this container type component.
;; It uses `end:` keyword followed by component name, which is `ds.page` here.


;; ========================= REMOVE THE COMMENT BELOW ==========================
-- end: ds.page
