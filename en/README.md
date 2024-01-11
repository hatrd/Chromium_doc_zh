# en

## Chromium\_doc\_zh

Chromium中文文档 for

https://www.chromium.org/developers/design-documents

## Design Documents

*   [Start Here: Background Reading](Start\_Here\_Background\_Reading/): Describes the high-level architecture of Chromium

    * [Multi-process Architecture](Start\_Here\_Background\_Reading/Multi-process\_Architecture.md)

    **Note**: Most of the rest of the design documents assume familiarity with the concepts explained in this document.

    * [How Chromium Displays Web Pages](Start\_Here\_Background\_Reading/How\_Chromium\_Displays\_Web\_Pages.md): Bottom-to-top overview of how WebKit is embedded in Chromium

### See Also: Design docs in source code

```
https://chromium.googlesource.com/chromium/src/+/master/docs/
```

### General Architecture

* [General Architecture](General\_Architecture/)
  * [Conventions and patterns for multi-platform development](General\_Architecture/Conventions\_and\_patterns\_for\_multi-platform\_development.md)
  * [Extension Security Architecture](General\_Architecture/Extension\_Security\_Architecture.md): How the extension system helps reduce the severity of extension vulnerabilities
  * [HW Video Acceleration in Chrom{e,ium}{,OS}](General\_Architecture/HW\_Video\_Acceleration\_in\_Chrom{eium}{OS}.md)
  * [Inter-process Communication](General\_Architecture/Inter-process\_Communication.md): How the browser, renderer, and plugin processes communicate
  * [Multi-process Resource Loading](General\_Architecture/Multi-process\_Resource\_Loading.md): How pages and images are loaded from the network into the renderer
  * [Plugin Architecture](General\_Architecture/Plugin\_Architecture.md)
  * [Process Models](General\_Architecture/Process\_Models.md): Our strategies for creating new renderer processes
  * [Profile Architecture](General\_Architecture/Profile\_Architecture.md)
  * [SafeBrowsing](General\_Architecture/SafeBrowsing.md)
  * [Sandbox](General\_Architecture/Sandbox.md)
  * [Security Architecture](General\_Architecture/Security\_Architecture.md): How Chromium's sandboxed rendering engine helps protect against malware
  * [Startup](General\_Architecture/Startup.md)
  * [Threading](General\_Architecture/Threading.md): How to use threads in Chromium Also see the documentation for [V8](http://code.google.com/apis/v8/), which is the JavaScript engine used within Chromium.
* [UI Framework](UI\_Framework/)
  * [UI Development Practices](UI\_Framework/UI\_Development\_Practices.md): Best practices for UI development inside and outside of Chrome's content areas.
  * [Views framework](UI\_Framework/Views\_framework.md): Our UI layout layer used on Windows/Chrome OS.
  * [views Windowing system](UI\_Framework/views\_Windowing\_system.md): How to build dialog boxes and other windowed UI using views.
  * [Aura](UI\_Framework/Aura.md): Chrome's next generation hardware accelerated UI framework, and the new ChromeOS window manager built using it.
  * [NativeControls](UI\_Framework/NativeControls.md): using platform-native widgets in views.
  * Focus and Activation with Views and Aura.
* [Graphics](Graphics/)
  * [Overview](Graphics/Overview.md)
  * [GPU Accelerated Compositing in Chrome](Graphics/GPU\_Accelerated\_Compositing\_in\_Chrome.md)
  * [GPU Feature Status Dashboard](Graphics/GPU\_Feature\_Status\_Dashboard.md)
  * [Rendering Architecture Diagrams](Graphics/Rendering\_Architecture\_Diagrams.md)
  * [Graphics and Skia](Graphics/Graphics\_and\_Skia.md)
  * [RenderText and Chrome UI text drawing](Graphics/RenderText\_and\_Chrome\_UI\_text\_drawing.md)
  * [GPU Command Buffer](Graphics/GPU\_Command\_Buffer.md)
  * [GPU Program Caching](Graphics/GPU\_Program\_Caching.md)
  * [Compositing in Blink/WebCore](Graphics/Compositing\_in\_Blink\_WebCore.md)
  * [Compositor Thread Architecture](Graphics/Compositor\_Thread\_Architecture.md)
  * [Rendering Benchmarks](Graphics/Rendering\_Benchmarks.md)
  * [Impl-side Painting](Graphics/Impl-side\_Painting.md)
  * [Video Playback and Compositor](Graphics/Video\_Playback\_and\_Compositor.md)
  * [ANGLE architecture presentation](Graphics/ANGLE\_architecture\_presentation.md)
* [Network stack](Network\_stack/)
  * [Overview](Network\_stack/Overview.md)
  * [Network Stack Objectives](Network\_stack/Network\_Stack\_Objectives.md)
  * [Crypto](Network\_stack/Crypto.md)
  * [Disk Cache](Network\_stack/Disk\_Cache.md)
  * [HTTP Cache](Network\_stack/HTTP\_Cache.md)
  * [Out of Process Proxy Resolving Draft \[unimplemented\]](Network\_stack/Out\_of\_Process\_Proxy\_Resolving\_Draft\_\[unimplemented].md)
  * [Proxy Settings and Fallback](Network\_stack/Proxy\_Settings\_and\_Fallback.md)
  * [Debugging network proxy problems](Network\_stack/Debugging\_network\_proxy\_problems.md)
  * [HTTP Authentication](Network\_stack/HTTP\_Authentication.md)
  * [View network internals tool](Network\_stack/View\_network\_internals\_tool.md)
  * [Make the web faster with SPDY pages](Network\_stack/Make\_the\_web\_faster\_with\_SPDY\_pages.md)
  * [the web even faster with QUIC pages](Network\_stack/\_the\_web\_even\_faster\_with\_QUIC\_pages.md)
  * [Cookie storage and retrieval](Network\_stack/Cookie\_storage\_and\_retrieval.md)
* [Security](Security/)
  * [Security Overview](Security/Security\_Overview.md)
  * [Protecting Cached User Data](Security/Protecting\_Cached\_User\_Data.md)
  * [System Hardening](Security/System\_Hardening.md)
  * [Chaps Technical Design](Security/Chaps\_Technical\_Design.md)
  * [TPM Usage](Security/TPM\_Usage.md)
  * [Per-page Suborigins](Security/Per-page\_Suborigins.md)
  * [Encrypted Partition Recovery](Security/Encrypted\_Partition\_Recovery.md)
* [Input](Input/)
  * See[chromium input](Input/chromium\_input.md)for design docs and other resources.
* [Rendering](Rendering/)
  * [Multi-column layout](Rendering/Multi-column\_layout.md)
  * [Style Invalidation in Blink](Rendering/Style\_Invalidation\_in\_Blink.md)
  * [Blink Coordinate Spaces](Rendering/Blink\_Coordinate\_Spaces.md)
* [Building](Building/)
  * [IDL build](Building/IDL\_build.md)
  * [IDL compiler](Building/IDL\_compiler.md)
  * See also the documentation for [GYP, the build script generation tool.](Building/GYP\_the\_build\_script\_generation\_tool..md)
* [Testing](Testing/)
  * [Layout test results dashboard](Testing/Layout\_test\_results\_dashboard.md)
  * [Generic theme for Test Shell](Testing/Generic\_theme\_for\_Test\_Shell.md)
  * [Moving LayoutTests fully upstream](Testing/Moving\_LayoutTests\_fully\_upstream.md)
* [Feature-Specific](Feature-Specific/)
  * [about:conflicts](Feature-Specific/aboutconflicts.md)
  * [Accessibility](Feature-Specific/Accessibility.md): An outline of current (and coming) accessibility support.
  * [Auto-Throttled Screen Capture and Mirroring](Feature-Specific/Auto-Throttled\_Screen\_Capture\_and\_Mirroring.md)
  * [Browser Window](Feature-Specific/Browser\_Window.md)
  * [Chromium Print Proxy](Feature-Specific/Chromium\_Print\_Proxy.md): Enables a cloud print service for legacy printers and future cloud-aware printers.
  * [Constrained Popup Windows](Feature-Specific/Constrained\_Popup\_Windows.md)
  * [Desktop Notifications](Feature-Specific/Desktop\_Notifications.md)
  * [DirectWrite Font Cache for Chrome on Windows](Feature-Specific/DirectWrite\_Font\_Cache\_for\_Chrome\_on\_Windows.md)
  * [DNS Prefetching](Feature-Specific/DNS\_Prefetching.md): Reducing perceived latency by resolving domain names before a user tries to follow a link
  * [Embedding Flash Fullscreen in the Browser Window](Feature-Specific/Embedding\_Flash\_Fullscreen\_in\_the\_Browser\_Window.md)
  * [Extensions: Design documents and proposed APIs. ](Feature-Specific/Extensions\_Design\_documents\_and\_proposed\_APIs..md): Design documents and proposed APIs.
  * [Find Bar](Feature-Specific/Find\_Bar.md)
  * [Form Autofill](Feature-Specific/Form\_Autofill.md): A feature to automatically fill out an html form with appropriate data.
  * [Geolocation](Feature-Specific/Geolocation.md): Adding support for [W3C Geolocation API](http://www.w3.org/TR/geolocation-API/) using native WebKit bindings.
  * [IDN in Google Chrome](Feature-Specific/IDN\_in\_Google\_Chrome.md)
  * [IndexedDB (early draft)](Feature-Specific/IndexedDB\_\_early\_draft\_.md)
  * [Info Bars](Feature-Specific/Info\_Bars.md)
  * [Installer](Feature-Specific/Installer.md): Registry entries and shortcuts
  * [Instant](Feature-Specific/Instant.md)
  * [Isolated Sites](Feature-Specific/Isolated\_Sites.md)
  * [Linux Resources and Localized Strings](Feature-Specific/Linux\_Resources\_and\_Localized\_Strings.md): Loading data resources and localized strings on Linux.
  * [Media Router & Web Presentation API](Feature-Specific/Media\_Router\_&\_Web\_Presentation\_API.md)
  * [Memory Usage Backgrounder](Feature-Specific/Memory\_Usage\_Backgrounder.md): Some information on how we measure memory in Chromium.
  * [Mouse Lock](Feature-Specific/Mouse\_Lock.md)
  * [Omnibox Autocomplete](../zh/UI\_Framework/views\_Windowing\_system.md): While typing into the omnibox, Chromium searches for and suggests possible completions.
    * [HistoryQuickProvider](Feature-Specific/Omnibox\_Autocomplete/): Suggests completions from the user's historical site visits.
  * [Omnibox/IME Coordination](Feature-Specific/Omnibox\_IME\_Coordination.md)
  * [Ozone Porting Abstraction](Feature-Specific/Ozone\_Porting\_Abstraction.md)
  * [Password Generation](Feature-Specific/Password\_Generation.md)
  * [Pepper plugin implementation](Feature-Specific/Pepper\_plugin\_implementation.md)
  * [Plugin Power Saver](Feature-Specific/Plugin\_Power\_Saver.md)
  * [Preferences](Feature-Specific/Preferences.md)
  * [Prerender](Feature-Specific/Prerender.md)
  * [Print Preview](Feature-Specific/Print\_Preview.md)
  * [Printing](Feature-Specific/Printing.md)
  * [Rect-based event targeting in views](Feature-Specific/Rect-based\_event\_targeting\_in\_views.md): Making it easier to target views elements with touch.
  * [Replace the modal cookie prompt](Feature-Specific/Replace\_the\_modal\_cookie\_prompt.md)
  * [SafeSearch](Feature-Specific/SafeSearch.md)
  * [Sane Time](Feature-Specific/Sane\_Time.md): Determining an accurate time in Chrome
  * [Secure Web Proxy](Feature-Specific/Secure\_Web\_Proxy.md)
  * [Service Processes](Feature-Specific/Service\_Processes.md)
  * [Site Isolation](Feature-Specific/Site\_Isolation.md): In-progress effort to improve Chromium's process model for security between web sites.
  * [Software Updates: Courgette](Feature-Specific/Software\_Updates\_Courgette.md)
  * [Sync](Feature-Specific/Sync.md)
  * [Tab Helpers](Feature-Specific/Tab\_Helpers.md)
  * [Tab to search](Feature-Specific/Tab\_to\_search.md): How to have the Omnibox automatically provide tab to search for your site.
  * [Tabtastic2 Requirements](Feature-Specific/Tabtastic2\_Requirements.md)
  * [Temporary downloads](Feature-Specific/Temporary\_downloads.md)
  * [Time Sources](Feature-Specific/Time\_Sources.md): Determining the time on a Chrome OS device
  * [TimeTicks](Feature-Specific/TimeTicks.md): How our monotonic timer, TimeTicks, works on different OSes
  * [UI Mirroring Infrastructure](Feature-Specific/UI\_Mirroring\_Infrastructure.md): Describes the UI framework in ChromeViews that allows mirroring the browser UI in RTL locales such as Hebrew and Arabic.
  * [UI Localization](Feature-Specific/UI\_Localization.md): Describes how localized strings get added to Chromium.
  * [User scripts](Feature-Specific/User\_scripts.md): Information on Chromium's support for user scripts.
  * [Video](Feature-Specific/Video.md)
  * [WebSocket](Feature-Specific/WebSocket.md): Enables Web applications to maintain bidirectional communications with server-side processes.
  * [Web MIDI](Feature-Specific/Web\_MIDI.md)
  * [WebNavigation API internals](Feature-Specific/WebNavigation\_API\_internals.md)
* [OS-Specific](OS-Specific/)
  * [Android](OS-Specific/Android/)
    * [Java Resources on Android](OS-Specific/Android/Java\_Resources\_on\_Android.md)
    * [JNI Bindings](Feature-Specific/Omnibox\_Autocomplete/HistoryQuickProvider.md)
    * [WebView code organization](OS-Specific/Android/WebView\_code\_organization.md)
  * [Chrome OS](OS-Specific/Android/JNI\_Bindings.md)
    * See the [Chrome OS design documents section.](OS-Specific/Chrome\_OS/)section.
  * [Mac OS X](OS-Specific/Chrome\_OS/Chrome\_OS\_design\_documents\_section..md)
    * [AppleScript Support](OS-Specific/Mac\_OS\_X/)
    * [BrowserWindowController Object Ownership](OS-Specific/Mac\_OS\_X/AppleScript\_Support.md)
    * [Confirm to Quit](OS-Specific/Mac\_OS\_X/BrowserWindowController\_Object\_Ownership.md)
    * [Mac App Mode (Draft)](OS-Specific/Mac\_OS\_X/Confirm\_to\_Quit.md)
    * [Mac Fullscreen Mode (Draft)](OS-Specific/Mac\_OS\_X/Mac\_App\_Mode\_\_Draft\_.md)
    * [Mac NPAPI Plugin Hosting](OS-Specific/Mac\_OS\_X/Mac\_Fullscreen\_Mode\_\_Draft\_.md)
    * [Mac specific notes on UI Localization](OS-Specific/Mac\_OS\_X/Mac\_NPAPI\_Plugin\_Hosting.md)
    * [Menus, Hotkeys, & Command Dispatch](OS-Specific/Mac\_OS\_X/Mac\_specific\_notes\_on\_UI\_Localization.md)
    * [Notes from meeting on IOSurface usage and semantics](OS-Specific/Mac\_OS\_X/Menus\_Hotkeys\_&\_Command\_Dispatch.md)
    * [OS X Interprocess Communication (Obsolete)](OS-Specific/Mac\_OS\_X/Notes\_from\_meeting\_on\_IOSurface\_usage\_and\_semantics.md)
    * [Password Manager/Keychain Integration](OS-Specific/Mac\_OS\_X/OS\_X\_Interprocess\_Communication\_\_Obsolete\_.md)
    * [Sandboxing Design](OS-Specific/Mac\_OS\_X/Password\_Manager\_Keychain\_Integration.md)
    * [Tab Strip Design (Includes tab layout and tab dragging)](OS-Specific/Mac\_OS\_X/Sandboxing\_Design.md)
    * [Wrench Menu Buttons](OS-Specific/Mac\_OS\_X/Tab\_Strip\_Design\_\_Includes\_tab\_layout\_and\_tab\_dragging\_.md)
* [Other](Other/)
  * [64-bit Support](Other/64-bit\_Support.md)
  * [Browser Components / Layered Components](Other/Browser\_Components\_\_\_Layered\_Components.md)
  * [Closure Compiling Chrome Code](Other/Closure\_Compiling\_Chrome\_Code.md)
  * [content module / content API](Other/content\_module\_\_\_content\_API.md)
  * [Design docs that still need to be written (wiki)](Other/Design\_docs\_that\_still\_need\_to\_be\_written\_\_wiki\_.md)
  * [In progress refactoring of key browser-process architecture for porting](Other/In\_progress\_refactoring\_of\_key\_browser-process\_architecture\_for\_porting.md)
  * [Network Experiments](Other/Network\_Experiments.md)
  * [Transitioning InlineBoxes from floats to LayoutUnits](Other/Transitioning\_InlineBoxes\_from\_floats\_to\_LayoutUnits.md)
