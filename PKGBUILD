pkgbase = ttf-ms-win11

pkgname=(${pkgbase}{,-japanese,-korean,-sea,-thai,-zh_cn,-zh_tw,-other})
pkgver=10.0.22631.2428
pkgrel=1
arch=(any)
url="https://learn.microsoft.com/en-us/typography/"
license=(custom)
provides=(ttf-font)
conflicts=(ttf-vista-fonts)
makedepends=(udisks2 p7zip)

_iso_filename = "win11.iso"
source=("${_iso_filename}::https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/22631.2428.231001-0608.23H2_NI_RELEASE_SVC_REFRESH_CLIENTENTERPRISEEVAL_OEMRET_x64FRE_en-us.iso")
noextract=("${_iso_filename}")

_ttf_ms_win11=(
########################################################################################
# Normal         Bold          Italic        Bold+Italic    # Full name                #
########################################################################################
arial.ttf      arialbd.ttf    ariali.ttf     arialbi.ttf    # Arial
ariblk.ttf                                                  # Arial Black
bahnschrift.ttf                                             # Bahnschrift
calibri.ttf    calibrib.ttf   calibrii.ttf   calibriz.ttf   # Calibri
calibril.ttf                  calibrili.ttf                 # Calibri Light
cambria.ttc    cambriab.ttf   cambriai.ttf   cambriaz.ttf   # Cambria
Candara.ttf    Candarab.ttf   Candarai.ttf   Candaraz.ttf   # Candara
Candaral.ttf                  Candarali.ttf                 # Candara Light
comic.ttf      comicbd.ttf    comici.ttf     comicz.ttf     # Comic Sans MS
consola.ttf    consolab.ttf   consolai.ttf   consolaz.ttf   # Consolas
constan.ttf    constanb.ttf   constani.ttf   constanz.ttf   # Constantia
corbel.ttf     corbelb.ttf    corbeli.ttf    corbelz.ttf    # Corbel
corbell.ttf                   corbelli.ttf                  # Corbel Light
cour.ttf       courbd.ttf     couri.ttf      courbi.ttf     # Courier New
framd.ttf                     framdit.ttf                   # Franklin Gothic Medium
Gabriola.ttf                                                # Gabriola
georgia.ttf    georgiab.ttf   georgiai.ttf   georgiaz.ttf   # Georgia
#holomdl2.ttf                                               # HoloLens MDL2 Assets
impact.ttf                                                  # Impact
Inkfree.ttf                                                 # Ink Free
l_10646.ttf                                                 # Lucida Sans Unicode
lucon.ttf                                                   # Lucida Console
marlett.ttf                                                 # Marlett
micross.ttf                                                 # Microsoft Sans Serifc
pala.ttf       palab.ttf      palai.ttf      palabi.ttf     # Palatino Linotype
segmdl2.ttf                                                 # Segoe MDL2 Assets
SegoeIcons.ttf                                              # Segoe Fluent Icons
segoepr.ttf    segoeprb.ttf                                 # Segoe Print
segoesc.ttf    segoescb.ttf                                 # Segoe Script
segoeui.ttf    segoeuib.ttf   segoeuii.ttf   segoeuiz.ttf   # Segoe UI
segoeuil.ttf                  seguili.ttf                   # Segoe UI Light
segoeuisl.ttf                 seguisli.ttf                  # Segoe UI Semilight
seguibl.ttf                   seguibli.ttf                  # Segoe UI Black
seguiemj.ttf                                                # Segoe UI Emoji
seguihis.ttf                                                # Segoe UI Historic
seguisb.ttf                   seguisbi.ttf                  # Segoe UI Semibold
seguisym.ttf                                                # Segoe UI Symbol
SegUIVar.ttf                                                # Segoe UI Variable
SitkaVF.ttf                   SitkaVF-Italic.ttf            # Sitka
sylfaen.ttf                                                 # Sylfaen
symbol.ttf                                                  # Symbol
tahoma.ttf     tahomabd.ttf                                 # Tahoma
times.ttf      timesbd.ttf    timesi.ttf     timesbi.ttf    # Times New Roman
trebuc.ttf     trebucbd.ttf   trebucit.ttf   trebucbi.ttf   # Trebuchet MS
verdana.ttf    verdanab.ttf   verdanai.ttf   verdanaz.ttf   # Verdana
webdings.ttf                                                # Webdings
wingding.ttf                                                # Wingdings
)

_ttf_ms_win11_japanese=(
#########################################################################################
# Normal         Bold          Italic        Bold+Italic    #  Full name                #
#########################################################################################
msgothic.ttc                                                # MS Gothic
YuGothR.ttc   YuGothB.ttc                                   # Yu Gothic
YuGothM.ttc                                                 # Yu Gothic Medium
YuGothL.ttc                                                 # Yu Gothic Light
)

_ttf_ms_win11_korean=(
#########################################################################################
# Normal         Bold          Italic        Bold+Italic    #  Full name                #
#########################################################################################
malgun.ttf     malgunbd.ttf                                 # Malgun Gothic
malgunsl.ttf                                                # Malgun Gothic Semilight
)

_ttf_ms_win11_sea=(
#########################################################################################
# Normal         Bold          Italic        Bold+Italic    #  Full name                #
#########################################################################################
javatext.ttf                                                # Javanese Text
himalaya.ttf                                                # Microsoft Himalaya
ntailu.ttf     ntailub.ttf                                  # Microsoft New Tai Lue
phagspa.ttf    phagspab.ttf                                 # Microsoft PhagsPa
taile.ttf      taileb.ttf                                   # Microsoft Tai Le
msyi.ttf                                                    # Microsoft Yi Baiti
monbaiti.ttf                                                # Mongolian Baiti
mmrtext.ttf    mmrtextb.ttf                                 # Myanmar Text
Nirmala.ttf    NirmalaB.ttf                                 # Nirmala UI
NirmalaS.ttf                                                # Nirmala UI Semilight
)

_ttf_ms_win11_thai=(
#########################################################################################
# Normal         Bold          Italic        Bold+Italic    #  Full name                #
#########################################################################################
LeelawUI.ttf   LeelaUIb.ttf                                 # Leelawadee UI
LeelUIsl.ttf                                                # Leelawadee UI Semilight
)

_ttf_ms_win11_zh_cn=( # Chinese (Simplified)
#########################################################################################
# Normal         Bold          Italic        Bold+Italic    #  Full name                #
#########################################################################################
simsun.ttc                                                  # NSimSun
simsunb.ttf                                                 # SimSun-ExtB
msyh.ttc       msyhbd.ttc                                   # Microsoft YaHei
msyhl.ttc                                                   # Microsoft YaHei Light
)

_ttf_ms_win11_zh_tw=( # Chinese (Traditional)
#########################################################################################
# Normal         Bold          Italic        Bold+Italic    #  Full name                #
#########################################################################################
msjh.ttc       msjhbd.ttc                                   # Microsoft JhengHei
msjhl.ttc                                                   # Microsoft JhengHei Light
mingliub.ttc                                                # MingLiU_HKSCS-ExtB
)

_ttf_ms_win11_other=(
#########################################################################################
# Normal         Bold          Italic        Bold+Italic    #  Full name                #
#########################################################################################
ebrima.ttf     ebrimabd.ttf                                 # Ebrima
gadugi.ttf     gadugib.ttf                                  # Gadugi
mvboli.ttf                                                  # MV Boli
)

sha256sums=("")


prepare() {
    7z e ${_iso_filename} -o "${srcdir}/" sources/install.wim
    mkdir -p "${srcdir}/contents"
    7z e "${srcdir}/install.wim" -o "${srcdir}/contents/"  Windows/{Fonts/"*".{ttf,ttc},System32/Licenses/neutral/"*"/"*"/license.rtf}
}

_per_package() {
    conflicts+=(${pkgname/11/8} ${pkgname/11/10} ttf-win7-fonts${pkgname##*11})
    for ttf_ in "${@}"; do 
        install -Dm644 "${srcdir}/contents/${ttf_}" -t "${pkgdir}/usr/share/fonts/TTF"
    done
    
    install -Dm644 "${srcdir}/contents/license.rtf" -t "${pkgdir}/usr/share/licenses/${pkgname}"
}

package_ttf-ms-win11() {
    pkgdesc='Microsoft Windows 11 TrueType fonts'
    provides+=(emoji-font ttf-tahoma ttf-ms-fonts)
    conflicts+=(ttf-tahoma ttf-ms-fonts)
    _package ${_ttf_ms_win11[@]}
}

package_ttf-ms-win11-japanese() {
    pkgdesc='Microsoft Windows 11 Japanese TrueType fonts'
    _package ${_ttf_ms_win11_japanese[@]}
}

package_ttf-ms-win11-korean() {
    pkgdesc='Microsoft Windows 11 Korean TrueType fonts'
    _package ${_ttf_ms_win11_korean[@]}
}

package_ttf-ms-win11-sea() {
    pkgdesc='Microsoft Windows 11 Southeast Asian TrueType fonts'
    _package ${_ttf_ms_win11_sea[@]}
}

package_ttf-ms-win11-thai() {
    pkgdesc='Microsoft Windows 11 Thai TrueType fonts'
    _package ${_ttf_ms_win11_thai[@]}
}

package_ttf-ms-win11-zh_cn() {
    pkgdesc='Microsoft Windows 11 Simplified Chinese TrueType fonts'
    _package ${_ttf_ms_win11_zh_cn[@]}
}

package_ttf-ms-win11-zh_tw() {
    pkgdesc='Microsoft Windows 11 Traditional Chinese TrueType fonts'
    _package ${_ttf_ms_win11_zh_tw[@]}
}

package_ttf-ms-win11-other() {
    pkgdesc='Microsoft Windows 11 Other TrueType fonts'
    _package ${_ttf_ms_win11_other[@]}
}
