# ThemeX Email Templates

Custom HTML/CSS email templates for the ThemeX Digital Marketplace.

## Branding
- ThemeX logo is rebuilt with HTML/CSS; the supplied reference image is not embedded.
- Multicolor outline uses purple, blue, cyan, pink and orange.
- Only the logo outline rotates; the logo body and T remain fixed.
- ThemeX wordmark uses a colorful gradient.
- Header and footer use the same CSS-built logo.
- Email/card outlines and CTA buttons use the same colorful visual language.

## Templates
1. Login OTP
2. Password Reset OTP
3. Welcome
4. Marketing / New Products
5. Order Confirmation
6. Payment Receipt
7. Download Ready
8. Password Changed / Security Alert

## Order fields
Order ID, order date, product name, license, payment method, payment status,
customer email, subtotal, discount, tax/VAT, total paid, digital delivery and
download/order CTA.

## Variables
`{{user_name}}`, `{{otp}}`, `{{otp_expiry_minutes}}`, `{{product_name}}`,
`{{order_id}}`, `{{order_date}}`, `{{license_type}}`, `{{payment_method}}`,
`{{customer_email}}`, `{{subtotal}}`, `{{discount}}`, `{{tax}}`,
`{{order_total}}`, `{{order_url}}`, `{{download_url}}`.

## Email-client note
JavaScript is not relied upon for production delivery because Gmail, Outlook and
other email clients commonly block or strip JavaScript. CSS animations are also
client-dependent, with static gradients serving as the fallback.

Repository path: `email-templates/themex/`
