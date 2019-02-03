# Goal Explorer

GoalExplorer generates automated tests that directly triggers the functionality of interest. 
At the core of our solution is an accurate, statically-built model, called Screen Transition Graph (STG), of UI screens and transitions between these screens. 

This repo also contains the details of our empirical evaluation on 93 benchmark applications and 95 the most popular GooglePlay applications, with detailed app version, category, and size.

## Evaluation:

### Google Play

| App                                             | Category            | Version                | Size (KB) | Installs       |
|-------------------------------------------------|---------------------|------------------------|-----------|----------------|
| com.saq.android                                 | LIFESTYLE           |  5.1.5                 | 6.82      | 500,000+       |
| ca.autotrader.userapp                           | LIFESTYLE           |  6.6.0                 | 24.83     | 1,000,000+     |
| com.life360.android.safetymapd                  | LIFESTYLE           |  16.4.1                | 46.03     | 50,000,000+    |
| com.enflick.android.TextNow                     | SOCIAL              |  5.15.0                | 33.26     | 10,000,000+    |
| org.videolan.vlc                                | VIDEO PLAYER        |  3.0.13                | 23.49     | 100,000,000+   |
| absworkout.butt.homeworkout.fitness.loseweight  | HEALTH AND FITNESS  |  1.1.2.3               | 12.17     | 5,000,000+     |
| com.starbucks.mobilecard                        | FOOD AND DRINK      |  4.9.2                 | 36.89     | 10,000,000+    |
| com.google.android.stardroid                    | BOOK AND REFERENCE  |  1.9.2                 | 3.61      | 50,000,000+    |
| com.adobe.reader                                | PRODUCTIVITY        |  18.5.1.8311           | 86.72     | 100,000,000+   |
| com.walmart.android                             | SHOPPING            | 18.19                  | 50.43     | 10,000,000+    |
| digital.rbi.timhortons                          | FOOD AND DRINK      |  1.1.26                | 24.07     | 500,000+       |
| sixpack.sixpackabs.absworkout                   | HEALTH AND FITNESS  |  1.0.2                 | 12.50     | 10,000,000+    |
| com.nest.android                                | LIFESTYLE           |  5.23.1.2              | 72.62     | 1,000,000+     |
| com.mcdonalds.app                               | FOOD AND DRINK      |  5.21.0                | 56.15     | 10,000,000+    |
| com.tattoodo.app                                | LIFESTYLE           |  2.4.7-r236            | 12.25     | 5,000,000+     |
| com.quran.labs.androidquran                     | BOOK AND REFERENCE  |  2.7.5-p1              | 2.59      | 10,000,000+    |
| com.microsoft.office.outlook                    | PRODUCTIVITY        |  2.2.172               | 4.51      | 100,000,000+   |
| com.shazam.android                              | MUSIC AND AUDIO     |  6.7.1-160719          | 30.51     | 100,000,000+   |
| com.scribd.app.reader0                          | BOOK AND REFERENCE  |  7.5.4                 | 33.17     | 10,000,000+    |
| messenger.chat.social.messenger                 | SOCIAL              | 1.24                   | 3.96      | 10,000,000+    |
| com.sei.android                                 | LIFESTYLE           |  3.1.6                 | 46.55     | 5,000,000+     |
| drawing.lessons.sketch.how.to.draw.portrait     | LIFESTYLE           |  2.4.7                 | 8.09      | 5,000,000+     |
| com.ftw_and_co.happn                            | LIFESTYLE           |  22.2.0                | 21.36     | 10,000,000+    |
| com.indeed.android.jobsearch                    | BUSINESS            | 4.9                    | 3.34      | 50,000,000+    |
| com.wayfair.wayfair                             | SHOPPING            |  4.93.13               | 54.59     | 5,000,000+     |
| com.abaenglish.videoclass                       | EDUCATION           |  2.5.1.1               | 61.50     | 10,000,000+    |
| com.sirma.mobile.bible.android                  | BOOK AND REFERENCE  |  7.5.3                 | 12.86     | 100,000,000+   |
| com.pizzahut.canada                             | LIFESTYLE           |  2.0.17                | 11.43     | 100,000+       |
| com.ebay.kijiji.ca                              | SHOPPING            |  6.21.1                | 23.07     | 5,000,000+     |
| com.pinterest                                   | SOCIAL              |  6.71.0                | 21.33     | 100,000,000+   |
| me.lyft.android                                 | MAPS AND NAVIGATION |  5.33.3.1529523297     | 24.74     | 10,000,000+    |
| com.easybrain.sudoku.android                    | BOARD               |  1.3.0                 | 13.52     | 10,000,000+    |
| com.audible.application                         | BOOK AND REFERENCE  |  2.28.0                | 25.85     | 100,000,000+   |
| com.daily.zodiac.signs.horoscope.palmistry      | ENTERTAINMENT       |  1.4.3                 | 40.88     | 10,000,000+    |
| com.discord                                     | COMMUNICATION       |  6.9.3                 | 38.30     | 50,000,000+    |
| com.wishabi.flipp                               | SHOPPING            | 9.2                    | 47.76     | 10,000,000+    |
| com.vsco.cam                                    | PHOTOGRAPHY         | 84                     | 44.74     | 50,000,000+    |
| com.olg.utility                                 | LIFESTYLE           |  2.2.0                 | 56.73     | 1,000,000+     |
| com.isysway.free.alquran                        | BOOK AND REFERENCE  |  3.1.0                 | 5.10      | 10,000,000+    |
| com.twitter.android                             | NEWS AND MAGAZINES  |  7.75.0-release.22     | 30.89     | 500,000,000+   |
| com.pelmorex.WeatherEyeAndroid                  | WEATHER             |  6.9.0.64              | 33.51     | 5,000,000+     |
| com.wattpad.tap                                 | BOOK AND REFERENCE  |  5.10.1                | 12.46     | 1,000,000+     |
| com.owl.clean                                   | TOOLS               |  2.0.1                 | 5.16      | 1,000,000+     |
| com.linkedin.android                            | SOCIAL              |  4.1.236               | 44.42     | 100,000,000+   |
| com.fifa.fifaapp.android                        | SPORTS              |  4.2.119               | 7.80      | 10,000,000+    |
| com.getepic.Epic                                | EDUCATION           |  0.9.3                 | 33.53     | 1,000,000+     |
| com.airmiles                                    | LIFESTYLE           |  3.5.0                 | 5.07      | 1,000,000+     |
| com.pizzapizza.production                       | LIFESTYLE           |  3.3.0                 | 17.48     | 100,000+       |
| com.waze                                        | MAPS AND NAVIGATION |  4.28.0.1              | 55.94     | 100,000,000+   |
| com.bitstrips.imoji                             | ENTERTAINMENT       |  10.34.193             | 35.84     | 100,000,000+   |
| com.google.android.apps.translate               | TOOLS               |  5.20.0.RC10.199570264 | 17.57     | 500,000,000+   |
| hotspotshield.android.vpn                       | TOOLS               |  6.6.1                 | 11.47     | 50,000,000+    |
| com.airbnb.android                              | TRAVEL AND LOCAL    | 18.43                  | 66.16     | 50,000,000+    |
| com.socialnmobile.dictapps.notepad.color.note   | PRODUCTIVITY        |  4.0.7                 | 1.32      | 100,000,000+   |
| com.andi.alquran.en                             | BOOK AND REFERENCE  |  2.6.22                | 15.70     | 500,000+       |
| com.adpog.diary                                 | LIFESTYLE           | 4.89                   | 4.08      | 10,000,000+    |
| com.clearchannel.iheartradio.controller         | MUSIC AND AUDIO     |  8.10.0                | 25.48     | 50,000,000+    |
| com.sec.android.easyMover                       | TOOLS               |  3.5.01.8              | 23.66     | 100,000,000+   |
| com.tubitv                                      | ENTERTAINMENT       |  2.16.3                | 15.74     | 10,000,000+    |
| net.daylio                                      | LIFESTYLE           |  1.16.4                | 8.59      | 5,000,000+     |
| com.drop.loyalty.android                        | LIFESTYLE           |  1.20.1                | 19.40     | 500,000+       |
| com.overdrive.mobile.android.mediaconsole       | BOOK AND REFERENCE  |  3.6.2                 | 8.50      | 5,000,000+     |
| easy.drum.set.free.finger.drums.kit             | MUSIC AND AUDIO     |  1.1.3                 | 10.03     | 5,000,000+     |
| com.tinder                                      | LIFESTYLE           |  9.2.0                 | 52.47     | 100,000,000+   |
| com.kobobooks.android                           | BOOK AND REFERENCE  |  7.2.21739             | 42.84     | 10,000,000+    |
| com.duolingo                                    | EDUCATION           |  3.106.5               | 21.72     | 100,000,000+   |
| com.dictionary                                  | BOOK AND REFERENCE  |  7.2.3                 | 9.80      | 10,000,000+    |
| homeworkout.homeworkouts.noequipment            | HEALTH AND FITNESS  |  1.0.15                | 14.59     | 50,000,000+    |
| com.microsoft.office.outlook                    | PRODUCTIVITY        |  2.2.172               | 47.91     | 100,000,000+   |
| com.jb.go.musicplayer.mp3player                 | MUSIC AND AUDIO     |  1.8.4                 | 17.54     | 10,000,000+    |
| com.soundcloud.android                          | MUSIC AND AUDIO     |  2018.07.30            | 20.49     | 100,000,000+   |
| com.google.android.apps.chromecast.app          | LIFESTYLE           |  1.29.20.20            | 21.43     | 50,000,000+    |
| com.thetransitapp.droid                         | MAPS AND NAVIGATION |  4.3.6                 | 11.58     | 5,000,000+     |
| net.zedge.android                               | PERSONALIZATION     |  5.42.19               | 12.57     | 100,000,000+   |
| com.fitbit.FitbitMobile                         | HEALTH AND FITNESS  | 2.79                   | 48.92     | 10,000,000+    |
| tv.peel.smartremote                             | ENTERTAINMENT       |  8.6.5                 | 8.17      | 100,000,000+   |
| com.ubercab                                     | MAPS AND NAVIGATION |  4.216.10002           | 53.76     | 100,000,000+   |
| org.ligi.survivalmanual                         | BOOK AND REFERENCE  | 3.9                    | 8.79      | 1,000,000+     |
| tv.twitch.android.app                           | ENTERTAINMENT       |  6.4.2                 | 29.23     | 50,000,000+    |
| com.contextlogic.wish                           | SHOPPING            |  4.20.1                | 14.77     | 100,000,000+   |
| com.google.android.apps.books                   | BOOK AND REFERENCE  |  3.12.15               | 10.59     | 1,000,000,000+ |
| com.mediagrif.lespac.app                        | LIFESTYLE           |  2.0.0                 | 5.65      | 100,000+       |
| com.athan                                       | LIFESTYLE           | 5.1                    | 30.53     | 1,000,000+     |
| com.soundcloud.android                          | MUSIC AND AUDIO     |  2018.06.12            | 20.49     | 100,000,000+   |
| com.reddit.frontpage                            | NEWS AND MAGAZINES  |  2.26.2                | 15.37     | 10,000,000+    |
| com.booking                                     | TRAVEL AND LOCAL    |  15.4.5                | 32.16     | 100,000,000+   |
| com.google.android.apps.youtube.music           | MUSIC AND AUDIO     |  2.35.56               | 20.07     | 100,000,000+   |
| org.zwanoo.android.speedtest                    | TOOLS               |  3.2.44                | 18.41     | 100,000,000+   |
| ch.protonmail.android                           | COMMUNICATION       |  1.6.1                 | 15.05     | 1,000,000+     |
| fm.castbox.audiobook.radio.podcast              | NEWS AND MAGAZINES  |  7.44.3-181128101      | 16.16     | 5,000,000+     |
| ca.bellmedia.cravetv                            | ENTERTAINMENT       |  3.2.2                 | 18.63     | 1,000,000+     |
| ca.tsn.mobile.android                           | SPORTS              | 1.18.0                 | 18.12     | 1,000,000+     |
| com.ncconsulting.skipthedishes_android          | FOOD AND DRINK      | 3.18.1                 | 13.66     | 1,000,000+     |
| com.spotify.music                               | MUSIC AND AUDIO     | 8.4.64.555             | 33.51     | 100,000,000+   |

### Benchmark

| Package Name                            | Version       | Size(KB)    |
|-----------------------------------------|---------------|-------------|
| net.jaqpot.netcounter                   |  0.13.1       | 0.203125    |
| com.google.android.divideandconquer     | 1.4           | 0.184570313 |
| com.threedlite.urforms                  | 1.12          | 0.342773438 |
| biz.gyrus.yaab                          |  1.10.1       | 0.37109375  |
| net.fercanet.LNM                        | 1.2           | 0.594726563 |
| org.passwordmaker.android               |  1.1.7        | 0.124023438 |
| com.twsitedapps.homemanager             | 2131099649    | 0.274414063 |
| org.balau.fakedawn                      | 1.3           | 0.223632813 |
| us.achromaticmetaphor.imcktg            | 0.4           | 0.19921875  |
| org.beide.bomber                        | 1             | 0.595703125 |
| com.addi                                | 1.98          | 20.59277344 |
| campyre.android                         |  1.0.1        | 0.802734375 |
| org.wordpress.android                   |  2.0 Alpha    | 1.444335938 |
| com.sunyata.kindmind                    |  1.0.0_BETA   | 0.422851563 |
| net.mandaria.tippytipper                |  1.1.3        | 0.135742188 |
| com.google.android.opengles.triangle    |  null         | 0.015625    |
| com.beust.android.translate             | 1.6           | 0.5078125   |
| org.jtb.alogcat                         |  2.6.1        | 0.279296875 |
| com.ringdroid                           | 2.6           | 0.333007813 |
| com.github.cetoolbox                    | 1             | 0.193359375 |
| com.android.lolcat                      | 2             | 0.203125    |
| com.example.amazed                      |  2.0.2        | 0.1640625   |
| com.evancharlton.mileage                |  3.1.1        | 0.529296875 |
| org.waxworlds.edam.importcontacts       | 1.1           | 0.205078125 |
| com.angrydoughnuts.android.alarmclock   | 1.9           | 0.322265625 |
| com.example.anycut                      | 0.5           | 0.17578125  |
| info.bpace.munchlife                    |  1.4.2        | 0.540039063 |
| org.swiftp                              | 1.25          | 0.0859375   |
| org.wikipedia                           |  1.2.1        | 1.356445313 |
| org.nerdcircus.android.klaxon           | 0.27          | 0.200195313 |
| com.nephoapp.anarxiv                    | 1             | 0.208007813 |
| edu.killerud.fileexplorer               | 1             | 0.181640625 |
| com.example.android.musicplayer         | 1             | 0.073242188 |
| fr.kwiatkowski.ApkTrack                 |  1.1h         | 0.620117188 |
| fr.keuse.rightsalert                    |  0.3a         | 0.197265625 |
| org.scoutant.blokish                    |  0.5.1        | 0.44140625  |
| de.freewarepoint.whohasmystuff          |  1.0.7        | 0.075195313 |
| com.everysoft.autoanswer                | 1.5           | 0.244140625 |
| de.zieren.rot13                         |  1.0.2        | 0.171875    |
| ch.blinkenlights.battery                | 2130968576    | 1.296875    |
| com.google.android.opengles.spritetext  |  null         | 0.030273438 |
| de.homac.Mirrored                       |  0.2.3        | 0.049804688 |
| in.shick.lockpatterngenerator           | 2.2           | 0.278320313 |
| jp.sblo.pandora.aGrep                   |  0.2.1        | 0.274414063 |
| com.google.android.photostream          | 1.1           | 0.28515625  |
| org.jfedor.frozenbubble                 | 1.12          | 0.63671875  |
| com.smorgasbork.hotdeath                |  1.0.7        | 7.833007813 |
| org.paulmach.textedit                   | 1.5           | 0.2734375   |
| com.frankcalise.h2droid                 | 1.5           | 0.213867188 |
| caldwell.ben.bites                      | 1.3           | 0.264648438 |
| com.teleca.jamendo                      |  1.0.5 [BETA] | 0.591796875 |
| org.totschnig.myexpenses                |  1.6.0        | 0.430664063 |
| com.hectorone.multismssender            | 2.6           | 0.223632813 |
| com.nloko.android.syncmypix             | 0.15          | 0.33984375  |
| com.hykwok.CurrencyConverter            | 1.1           | 0.2421875   |
| com.zachrattner.pockettalk              | 2.5           | 0.209960938 |
| com.commonsware.android.arXiv           |  2.0.22       | 0.670898438 |
| hu.vsza.adsdroid                        | 1.6           | 0.28515625  |
| a2dp.Vol                                |  2.11.12      | 0.5234375   |
| com.bretternst.URLazy                   |  1.0a         | 0.170898438 |
| cri.sanity                              | 2.11          | 0.606445313 |
| org.liberty.android.fantastischmemo     | 2131230964    | 0.9453125   |
| com.tum.yahtzee                         | 1.1           | 0.041992188 |
| i4nc4mp.myLockcomplete                  |  a3 revision  | 0.194335938 |
| org.smerty.zooborns                     |  1.4.4        | 0.038085938 |
| org.dnaq.dialer2                        | 2.9           | 0.3125      |
| com.chmod0.manpages                     | 1.51          | 0.205078125 |
| aarddict.android                        |  1.6.11       | 1.827148438 |
| marto.rtl_tcp_andro                     | 2.2           | 0.408203125 |
| eu.domob.angulo                         | 2131099649    | 0.1875      |
| jpf.android.diary                       | 1             | 0.022460938 |
| com.kvance.Nectroid                     |  1.2.4        | 0.278320313 |
| com.eleybourn.bookcatalogue             | 3.8           | 0.801757813 |
| com.zoffcc.applications.aagtl           |  1.0.31       | 0.470703125 |
| jp.gr.java_conf.hatalab.mnv             | 0.4           | 0.317382813 |
| com.kkinder.charmap                     |  1.0.1        | 0.174804688 |
| com.gluegadget.hndroid                  | 0.2           | 0.27734375  |
| com.irahul.worldclock                   | 0.6           | 1.100585938 |
| net.sf.andbatdog.batterydog             |  0.1.1        | 0.168945313 |
| com.templaro.opsiz.aka                  | 1             | 0.23046875  |
| com.fsck.k9                             | 3.512         | 2.630859375 |
| demo.killerud.gestures                  | 1             | 0.163085938 |
| com.morphoss.acal                       | 1.62          | 1.350585938 |
| org.jessies.dalvikexplorer              | 3.9           | 0.248046875 |
| com.bwx.bequick                         |  1.9.9.3      | 0.379882813 |
| com.android.spritemethodtest            |  null         | 0.046875    |
| hiof.enigma.android.soundboard          | 1             | 0.060546875 |
| org.tomdroid                            |  0.7.5        | 1.0546875   |
| es.senselesssolutions.gpl.weightchart   |  1.0.4        | 0.108398438 |
| org.liberty.android.fantastischmemo     | 2131230964    | 0.946289063 |
| net.everythingandroid.timer             |  1.1.0        | 0.196289063 |
