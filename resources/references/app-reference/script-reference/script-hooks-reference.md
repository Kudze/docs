# List of all available Hooks for Scripting

## Data Loading

All available Hooks that can be used to load additional data.

| Hook Name | Description | Available Data | Available Services |
|-----------|------------|----------------|--------------------|
| customer-group-registration-page-loaded<br>(`Shopware\Storefront\Page\Account\CustomerGroupRegistration\CustomerGroupRegistrationPageLoadedHook`) | Triggered when the CustomerGroupRegistrationPage is loaded<br> | page: `Shopware\Storefront\Page\Account\CustomerGroupRegistration\CustomerGroupRegistrationPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| account-guest-login-page-loaded<br>(`Shopware\Storefront\Page\Account\Login\AccountGuestLoginPageLoadedHook`) | Triggered when the AccountGuestLoginPage is loaded<br> | page: `Shopware\Storefront\Page\Account\Login\AccountLoginPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| account-login-page-loaded<br>(`Shopware\Storefront\Page\Account\Login\AccountLoginPageLoadedHook`) | Triggered when the AccountLoginPage is loaded<br> | page: `Shopware\Storefront\Page\Account\Login\AccountLoginPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| account-edit-order-page-loaded<br>(`Shopware\Storefront\Page\Account\Order\AccountEditOrderPageLoadedHook`) | Triggered when the AccountEditOrderPage is loaded<br> | page: `Shopware\Storefront\Page\Account\Order\AccountEditOrderPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| account-order-detail-page-loaded<br>(`Shopware\Storefront\Page\Account\Order\AccountOrderDetailPageLoadedHook`) | Triggered when the AccountOrderDetailPage is loaded<br> | page: `Shopware\Storefront\Page\Account\Order\AccountOrderDetailPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| account-order-page-loaded<br>(`Shopware\Storefront\Page\Account\Order\AccountOrderPageLoadedHook`) | Triggered when the AccountOrderPage is loaded<br> | page: `Shopware\Storefront\Page\Account\Order\AccountOrderPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| account-overview-page-loaded<br>(`Shopware\Storefront\Page\Account\Overview\AccountOverviewPageLoadedHook`) | Triggered when the AccountOverviewPage is loaded<br> | page: `Shopware\Storefront\Page\Account\Overview\AccountOverviewPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| account-payment-method-page-loaded<br>(`Shopware\Storefront\Page\Account\PaymentMethod\AccountPaymentMethodPageLoadedHook`) | Triggered when the AccountPaymentMethodPage is loaded<br> | page: `Shopware\Storefront\Page\Account\PaymentMethod\AccountPaymentMethodPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| account-profile-page-loaded<br>(`Shopware\Storefront\Page\Account\Profile\AccountProfilePageLoadedHook`) | Triggered when the AccountProfilePage is loaded<br> | page: `Shopware\Storefront\Page\Account\Profile\AccountProfilePage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| account-register-page-loaded<br>(`Shopware\Storefront\Page\Account\Register\AccountRegisterPageLoadedHook`) | Triggered when the AccountLoginPage is loaded<br> | page: `Shopware\Storefront\Page\Account\Login\AccountLoginPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| address-detail-page-loaded<br>(`Shopware\Storefront\Page\Address\Detail\AddressDetailPageLoadedHook`) | Triggered when the AddressDetailPage is loaded<br> | page: `Shopware\Storefront\Page\Address\Detail\AddressDetailPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| address-book-widget-loaded<br>(`Shopware\Storefront\Page\Address\Listing\AddressBookWidgetLoadedHook`) | Triggered when the AddressBookWidget is loaded<br> | page: `Shopware\Storefront\Page\Address\Listing\AddressListingPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| address-listing-page-loaded<br>(`Shopware\Storefront\Page\Address\Listing\AddressListingPageLoadedHook`) | Triggered when the AddressListingPage is loaded<br> | page: `Shopware\Storefront\Page\Address\Listing\AddressListingPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| checkout-cart-page-loaded<br>(`Shopware\Storefront\Page\Checkout\Cart\CheckoutCartPageLoadedHook`) | Triggered when the CheckoutCartPage is loaded<br> | page: `Shopware\Storefront\Page\Checkout\Cart\CheckoutCartPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| checkout-confirm-page-loaded<br>(`Shopware\Storefront\Page\Checkout\Confirm\CheckoutConfirmPageLoadedHook`) | Triggered when the CheckoutConfirmPage is loaded<br> | page: `Shopware\Storefront\Page\Checkout\Confirm\CheckoutConfirmPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| checkout-finish-page-loaded<br>(`Shopware\Storefront\Page\Checkout\Finish\CheckoutFinishPageLoadedHook`) | Triggered when the CheckoutFinishPage is loaded<br> | page: `Shopware\Storefront\Page\Checkout\Finish\CheckoutFinishPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| checkout-info-widget-loaded<br>(`Shopware\Storefront\Page\Checkout\Offcanvas\CheckoutInfoWidgetLoadedHook`) | Triggered when the CheckoutInfoWidget is loaded<br> | page: `Shopware\Storefront\Page\Checkout\Offcanvas\OffcanvasCartPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| checkout-offcanvas-widget-loaded<br>(`Shopware\Storefront\Page\Checkout\Offcanvas\CheckoutOffcanvasWidgetLoadedHook`) | Triggered when the CheckoutOffcanvasWidget is loaded<br> | page: `Shopware\Storefront\Page\Checkout\Offcanvas\OffcanvasCartPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| checkout-register-page-loaded<br>(`Shopware\Storefront\Page\Checkout\Register\CheckoutRegisterPageLoadedHook`) | Triggered when the CheckoutRegisterPage is loaded<br> | page: `Shopware\Storefront\Page\Checkout\Register\CheckoutRegisterPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| cms-page-loaded<br>(`Shopware\Storefront\Page\Cms\CmsPageLoadedHook`) | Triggered when a CmsPage is loaded<br> | page: `Shopware\Core\Content\Cms\CmsPageEntity`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| landing-page-loaded<br>(`Shopware\Storefront\Page\LandingPage\LandingPageLoadedHook`) | Triggered when the LandingPage is loaded<br> | page: `Shopware\Storefront\Page\LandingPage\LandingPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| maintenance-page-loaded<br>(`Shopware\Storefront\Page\Maintenance\MaintenancePageLoadedHook`) | Triggered when the MaintenancePage is loaded<br> | page: `Shopware\Storefront\Page\Maintenance\MaintenancePage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| navigation-page-loaded<br>(`Shopware\Storefront\Page\Navigation\NavigationPageLoadedHook`) | Triggered when the NavigationPage is loaded<br> | page: `Shopware\Storefront\Page\Navigation\NavigationPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| product-page-loaded<br>(`Shopware\Storefront\Page\Product\ProductPageLoadedHook`) | Triggered when the ProductPage is loaded<br> | page: `Shopware\Storefront\Page\Product\ProductPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| product-quick-view-widget-loaded<br>(`Shopware\Storefront\Page\Product\QuickView\ProductQuickViewWidgetLoadedHook`) | Triggered when the ProductQuickViewWidget is loaded<br> | page: `Shopware\Storefront\Page\Product\QuickView\MinimalQuickViewPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| product-reviews-loaded<br>(`Shopware\Storefront\Page\Product\Review\ProductReviewsWidgetLoadedHook`) | Triggered when the ProductReviewsWidget is loaded<br> | reviews: `Shopware\Storefront\Page\Product\Review\ReviewLoaderResult`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| search-page-loaded<br>(`Shopware\Storefront\Page\Search\SearchPageLoadedHook`) | Triggered when the SearchPage is loaded<br> | page: `Shopware\Storefront\Page\Search\SearchPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| search-widget-loaded<br>(`Shopware\Storefront\Page\Search\SearchWidgetLoadedHook`) | Triggered when the SearchWidget is loaded<br> | page: `Shopware\Storefront\Page\Search\SearchPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| sitemap-page-loaded<br>(`Shopware\Storefront\Page\Sitemap\SitemapPageLoadedHook`) | Triggered when the SitemapPage is loaded<br> | page: `Shopware\Storefront\Page\Sitemap\SitemapPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| suggest-page-loaded<br>(`Shopware\Storefront\Page\Suggest\SuggestPageLoadedHook`) | Triggered when the SuggestPage is loaded<br> | page: `Shopware\Storefront\Page\Suggest\SuggestPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| guest-wishlist-page-loaded<br>(`Shopware\Storefront\Page\Wishlist\GuestWishlistPageLoadedHook`) | Triggered when the GuestWishlistPage is loaded<br> | page: `Shopware\Storefront\Page\Wishlist\GuestWishlistPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| wishlist-page-loaded<br>(`Shopware\Storefront\Page\Wishlist\WishlistPageLoadedHook`) | Triggered when the WishlistPage is loaded<br> | page: `Shopware\Storefront\Page\Wishlist\WishlistPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| wishlist-widget-loaded<br>(`Shopware\Storefront\Page\Wishlist\WishlistWidgetLoadedHook`) | Triggered when the WishlistWidget is loaded<br> | page: `Shopware\Storefront\Page\Wishlist\WishlistPage`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| menu-offcanvas-pagelet-loaded<br>(`Shopware\Storefront\Pagelet\Menu\Offcanvas\MenuOffcanvasPageletLoadedHook`) | Triggered when the MenuOffcanvasPagelet is loaded<br> | page: `Shopware\Storefront\Pagelet\Menu\Offcanvas\MenuOffcanvasPagelet`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |
| guest-wishlist-pagelet-loaded<br>(`Shopware\Storefront\Pagelet\Wishlist\GuestWishlistPageletLoadedHook`) | Triggered when the GuestWishlistPagelet is loaded<br> | page: `Shopware\Storefront\Pagelet\Wishlist\GuestWishlistPagelet`<br>context: `Shopware\Core\Framework\Context`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br> | repository: `Shopware\Core\Framework\DataAbstractionLayer\Facade\RepositoryFacade`<br>config: `Shopware\Core\System\SystemConfig\Facade\SystemConfigFacade`<br>store: `Shopware\Core\Framework\DataAbstractionLayer\Facade\SalesChannelRepositoryFacade`<br> |

## Cart Manipulation

All available Hooks that can be used to manipulate the cart.

| Hook Name | Description | Available Data | Available Services |
|-----------|------------|----------------|--------------------|
| cart<br>(`Shopware\Core\Checkout\Cart\Hook\CartHook`) | Triggered during the cart calculation process.<br> | cart: `Shopware\Core\Checkout\Cart\Cart`<br>salesChannelContext: `Shopware\Core\System\SalesChannel\SalesChannelContext`<br>context: `Shopware\Core\Framework\Context`<br> | cart: `Shopware\Core\Checkout\Cart\Facade\CartFacade`<br> |
