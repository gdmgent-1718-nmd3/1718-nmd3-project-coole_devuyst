---
layout   : ui-style-guide
permalink: design/ui-style-guide/typografie/
published: true
# Custom Page Variables
# ─────────────────────
title: Typografie
---

etage: alfa slab regular
etage: alfa slab regular	grootte: getal: 26, etage: 14

# Dit is een voorbeeldtitel

    @mixin titles{
        font-family: $font-family-titles;
        font-size:26px;
        line-height: 36px;
        font-weight: normal;
    }

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputate eleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac, enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellus viverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiam ultricies nisi vel augue. Curabitur ullamcorper ultricies nisi. Nam eget dui.

    @mixin paragraphs{
        font-family: $font-family-OpenSans;
        font-size:15px;
        line-height: 24px;
        font-weight: normal;
    }

Voorbeeld button
{:.btn .btn-outline-primary}

    @mixin buttons{
        font-family: $font-family-OpenSans;
        font-size:24px;
        line-height: 24px;
        font-weight: normal;
    }

![NotificationText]({{ '/assets/img/notificatie_tekst.png' | relative_url }}){:.w-25}

    @mixin notifications{
        font-family: $font-family-OpenSans;
        font-size:28px;
        line-height: 38px;
        font-weight: normal;
    }