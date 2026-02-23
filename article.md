---
jupyter:
  jupytext:
    formats: ipynb,md
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.3'
      jupytext_version: 1.19.1
  kernelspec:
    display_name: Python 3 (ipykernel)
    language: python
    name: python3
---

<!-- #region slideshow={"slide_type": ""} tags=["title"] -->
# Hidden Constellations: Legibility and Queer Sapphic Spatial History in New York City
<!-- #endregion -->

<!-- #region tags=["contributor"] -->
 ### Yuchun  Zhang [![orcid](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0009-0007-9556-4413) 
Independent Researcher
<!-- #endregion -->

<!-- #region tags=["copyright"] -->
[![cc-by](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/) 
© Yuchun Zhang. Published by De Gruyter in cooperation with the University of Luxembourg Centre for Contemporary and Digital History. This is an Open Access article distributed under the terms of the [Creative Commons Attribution License CC-BY](https://creativecommons.org/licenses/by/4.0/)

<!-- #endregion -->

```python tags=["cover"]
from IPython.display import Image, display

display(Image("./media/bg6.jpg"))
```

<!-- #region tags=["keywords"] -->
queer sapphic space, documentary infrastructures, data integration, spatial history, cognitive mapping, legibility
<!-- #endregion -->

<!-- #region tags=["abstract"] -->
Queer sapphic spatial practices in New York City leave uneven documentary traces, making them difficult to study through conventional geospatial datasets. This article examines that unevenness as a problem of legibility and develops a layered evidentiary method for reading it historically. It assembles an address-based spatial corpus from multiple New York City sources produced under different documentary regimes, harmonizes a minimal shared schema, and geocodes entries where coordinates are missing. The address-based layer is organized at a decade scale and explored through an interactive timeline that enables source-aware comparison of where records cluster, thin out, or diverge, without treating any single dataset as definitive. The study also introduces a participant-generated register of ten interviews and sketch maps to support a parallel reading of relational and episodic spatial knowledge. Taken together, the project offers a source-critical way to interpret gaps in address-based spatial history as historically meaningful signals of legibility conditions.
<!-- #endregion -->

## Introduction: Absent, or Unheard?

<!-- #region citation-manager={"citations": {"txx6b": [{"id": "23211570/NKS3CRUD", "source": "zotero"}], "xv5jc": [{"id": "23211570/GF49PUCC", "source": "zotero"}]}} -->
New York City is routinely imagined as an urban archive of queer life. Yet when the object of inquiry shifts to queer sapphic worlds, the city becomes harder to locate on the map. The NYC LGBTQ Historic Sites Project documents 505 historic sites, but queer sapphic space remains numerically slight within contemporary inventories (<cite id="xv5jc"><a href="#zotero%7C23211570%2FGF49PUCC">(<i>NYC LGBTQ Historic Sites Project</i>, n.d.)</a></cite>). The Lesbian Bar Project’s list of the 36 remaining lesbian bars in the United States includes only a small handful in New York City (<cite id="txx6b"><a href="#zotero%7C23211570%2FNKS3CRUD">(<i>The Lesbian Bar Project | Watch Our Docuseries</i>, n.d.)</a></cite>). One entry in the NYC LGBTQ Historic Sites Project describes a well-known lesbian bar as “one of the city’s three remaining lesbian bars,” a phrasing that underscores how quickly such counts change and how precarious “presence” becomes when it is reduced to a short list. 
<!-- #endregion -->

This disparity is often read as a disappearance narrative, a vanishing of sapphic space from a city that otherwise presents itself as richly queer. The more difficult question is whether we are witnessing the disappearance of social worlds, or the disappearance of what is easily recordable. When queer urban history is told primarily through stable venues and durable addresses, it privileges what can be named, listed, and revisited by researchers, journalists, and preservationists. What falls outside these documentary genres may appear to fade, even when it continues to operate through other spatial forms.

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
What kind of history is being written when scarcity on a map is treated as scarcity in life? Is the story here one of a “hidden world,” or of a world that becomes visible only when it is already structured to be countable? Put differently, are we tracing queer sapphic space itself, or the archival and data infrastructures that decide what qualifies as space in the first place? 
<!-- #endregion -->

This article argues that, for queer sapphic histories, “space” does not consistently survive as an address. It often persists as a set of relational conditions: who is present, what kinds of recognition are possible, what forms of safety or risk attach to entry, and how atmospheres signal belonging without announcing it. As an interviewee in this study said, there is “more comfort” in a consciously sapphic space, not only because of who is there, but because the space is organized around shared expectations that may remain unspoken.
The analysis moves across three registers of evidence. It first examines how queer space becomes mappable history through documentary infrastructures and their categories. It then treats absence as patterned evidence, asking how gaps are produced across archives and datasets rather than treating them as mere missing data. Finally, it introduces a bottom-up evidentiary practice that places interviews and participant sketch maps alongside compiled records, not to “complete” the archive, but to clarify what address-based evidence cannot readily stabilize. Methodologically, the article treats legibility as an object of analysis and reads it through layered registers of evidence rather than a single map-based account.

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
## Definitions
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
### Sapphic
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
In this article, sapphic refers to people who experience emotional, romantic, sensual, or sexual attraction to women or non-men. The term is intentionally inclusive across gender identities and orientations, including nonbinary individuals and asexual people who experience romantic or emotional connections toward women or non-men. This framing is useful for the project because the communities most likely to be under-recorded often do not map cleanly onto stable institutional categories or directory labels.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
### Queer sapphic space
<!-- #endregion -->

<!-- #region citation-manager={"citations": {"bq6lv": [{"id": "23211570/JXEQQXKB", "source": "zotero"}], "xvdn9": [{"id": "23211570/ULLQ87LG", "source": "zotero"}]}} slideshow={"slide_type": ""} tags=["hermeneutics"] -->
Queer sapphic space is not treated as a stable set of venues, such as “lesbian bars,” but as a historically situated ecology of spatial practices through which sapphic desire, affiliation, and mutual recognition become legible to participants. In this study, the scope of the term extends beyond commercial nightlife to include events, pop-ups, and community gatherings, as well as semi-private domestic nodes such as living rooms and informal hosting circuits, and recurring routes that function as dependable pathways to contact, care, and safety. The goal is not to dilute the category, but to bring the unit of analysis closer to how queer sapphic life has often been sustained through intermittent assembling, selective disclosure, and relational infrastructures rather than permanent public addresses (<cite id="xvdn9"><a href="#zotero%7C23211570%2FULLQ87LG">(Halberstam, 2005)</a></cite>, <cite id="bq6lv"><a href="#zotero%7C23211570%2FJXEQQXKB">(Browne, 2009)</a></cite>).
<!-- #endregion -->

<!-- #region citation-manager={"citations": {"h2a41": [{"id": "23211570/TSJEMLS8", "source": "zotero"}], "odyxe": [{"id": "23211570/H8A3MZPK", "source": "zotero"}]}} slideshow={"slide_type": ""} tags=["hermeneutics"] -->
Operationally, the term names sites or spatial formations that become recurrently meaningful for sapphic participants as places of recognition, refuge, community-making, or desire, whether or not they publicly self-identify as lesbian or sapphic, and whether or not they are traceable through conventional datasets. This definition foregrounds practice over category, reflecting a guiding interpretive stance of the article: for queer sapphic histories, space is often better approached as a relational achievement than as a fixed container (<cite id="odyxe"><a href="#zotero%7C23211570%2FH8A3MZPK">(Massey, 2009)</a></cite>, <cite id="h2a41"><a href="#zotero%7C23211570%2FTSJEMLS8">(Nash &#38; Browne, 2016)</a></cite>).
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
## Evidence, Sources, and Legibility
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
### Documentary infrastructures and legibility
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
Urban queer histories often enter the record through documentary forms that can name, locate, and repeat “sites” over time, such as directories, media accounts, administrative files, and later heritage documentation. Within this evidentiary environment, queer space is most readily captured when it can be stabilized as a place with an address, a recognizable label, and a narratable claim of significance.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
In this article, “absence” is approached as evidence about legibility conditions. What does not appear may reflect how documentation is produced, what categories are available, and what kinds of disclosure are survivable in public records, rather than indicating straightforward social nonexistence.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
### Data sources
<!-- #endregion -->

<!-- #region citation-manager={"citations": {"2u83u": [{"id": "23211570/ETBUK2QK", "source": "zotero"}], "mjzjc": [{"id": "23211570/JSTJ8HPV", "source": "zotero"}], "npm0m": [{"id": "23211570/XLK7SXJA", "source": "zotero"}]}} slideshow={"slide_type": ""} -->
The address-based spatial corpus is compiled from three New York City–focused sources produced under different documentary regimes: the NYC LGBT Historic Sites Project, the Addresses Project, and Stegall’s scholarly reconstruction of lesbian bar history (<cite id="2u83u"><a href="#zotero%7C23211570%2FETBUK2QK">(Stegall, Gwendolyn, 2019)</a></cite>). Two national studies by Mattson provide a broader documentary frame for interpreting what commercial business listings can and cannot register when “bar history” is inferred from market-facing categories (<cite id="mjzjc"><a href="#zotero%7C23211570%2FJSTJ8HPV">(Mattson, 2019)</a></cite>, <cite id="npm0m"><a href="#zotero%7C23211570%2FXLK7SXJA">(Mattson, 2021)</a></cite>). NYC Open Data supports the workflow with basemaps, neighborhood boundaries, and reference layers used during standardization and geocoding. In addition to the address-based corpus, the article draws on participant-generated materials from ten research sessions, each producing an interview transcript and an accompanying sketch map. These materials are treated as a distinct evidentiary layer and are described separately in ([Section 4.5](#spatial-precision-logic)).
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
Bringing these sources into a shared corpus requires harmonization and spatialization decisions that affect what becomes comparable across decades. These operations are treated as part of the article’s evidentiary stance: they make visible how documentary claims are assembled for mapping.
<!-- #endregion -->

```python jdh={"module": "object", "object": {"source": ["Source overview"]}} slideshow={"slide_type": ""} tags=["table-Source-overview-*"]
import pandas as pd
df = pd.read_excel("./data/Table 1. Source overview.xlsx")
df
```

<!-- #region slideshow={"slide_type": ""} -->
### Reading stance
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
This article does not aim to produce a complete inventory of queer sapphic space. Instead, it builds a shared frame for reading heterogeneous traces side by side, so that overlaps, divergences, and uneven density can be interpreted in relation to evidence conditions rather than immediately as direct measures of social presence.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
Within this frame, the address-based corpus is read as a record of what can be stabilized as mappable evidence under particular documentary regimes, including their categories, verification norms, and survivable forms of publicity. Participant materials are read as a parallel evidentiary register that helps interpret the limits and stakes of that stabilization by making legibility, access, and spatial practice available in a form that is not reducible to address-based traceability.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
## Method: A Layered Evidentiary Workflow
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
### Building a spatial corpus from heterogeneous records
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
This project begins from the premise that queer sapphic spatial history is unevenly documented across records produced for different purposes and under different constraints. Rather than privileging any single dataset as authoritative, the workflow assembles a spatial corpus by compiling multiple sources, retaining provenance, and aligning them through a minimal shared schema. This approach enables comparison across decades while keeping the documentary origins and limitations of each record visible. The aim is not to synthesize a complete inventory, but to construct a comparative evidentiary surface through which patterns, gaps, and divergences can be read historically.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
### Schema harmonization and temporal normalization
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
Records from different sources are harmonized through a small set of shared fields that preserve provenance while enabling cross-source comparison. These include canonicalized place names, site-type tags, source references, temporal signals, and spatial-precision indicators. Harmonization does not resolve discrepancies between sources; instead, it standardizes how those discrepancies are recorded and made comparable.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
Temporal information is normalized to a decade scale based on structured fields such as reported decades, start and end years, or bounded date ranges. This normalization supports a timeline-based reading that foregrounds documentary rhythm and density rather than smoothing temporal uncertainty into falsely precise year-level claims. Where no structured temporal signal is available, time precision is explicitly marked as missing rather than inferred from narrative description. 
<!-- #endregion -->

```python slideshow={"slide_type": ""} tags=["table-Harmonized-field-dictionary-*", "data-table", "hermeneutics"] jdh={"module": "object", "object": {"source": ["Harmonized field dictionary"]}}
# pandas package needs to be added to the requirements.txt 's file 
import pandas as pd
df = pd.read_excel("./data/Table 2. Harmonized field dictionary.xlsx")
df
```

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
The full harmonization workflow is provided in the repository. The core temporal normalization logic is excerpted below.
<!-- #endregion -->

```python slideshow={"slide_type": ""} tags=["Code-Harmonization-script-*", "hermeneutics"]
def finalize_decades_and_basis(
    reported_decades: pd.Series,
    derived_decades: pd.Series,
    source_tag: str
) -> tuple[pd.Series, pd.Series]:

    decades_norm = np.where(
        reported_decades.map(len) > 0,
        reported_decades.map(json.dumps),
        np.where(
            derived_decades.map(len) > 0,
            derived_decades.map(json.dumps),
            json.dumps([])
        )
    )

    time_basis = np.select(
        [
            reported_decades.map(len) > 0,
            (reported_decades.map(len) == 0) & (derived_decades.map(len) > 0)
        ],
        [
            f"{source_tag}.decades_reported",
            f"{source_tag}.decades_derived_from_bounds"
        ],
        default=f"{source_tag}.decades_missing"
    )

    return decades_norm, time_basis
```

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
### Spatialization, geocoding, and limits of point precision
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
Entries that lack explicit coordinates are spatialized through address reconstruction and automated geocoding where appropriate. This process attends to historical street naming, venue relocation, and the frequent use of non-address-based locational descriptions in historical sources. In many cases, point-level precision is neither warranted nor recoverable. Street intersections, street segments, neighborhood-level descriptions, and name-only references are therefore treated as valid spatial claims rather than residual errors. They are retained as non-pointable location claims and recorded via precision classes, even when no geometry is generated for point-based mapping.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
Automated geocoding is understood as a provisional operation. Geocoding failures are retained as evidence of the limits of machine-readable addressability rather than silently corrected or discarded. Where stable addresses can be verified through external reference, manual spatial verification is applied selectively, with original geocoding failures preserved for auditability. Where spatialization remains unresolved, entries are retained without coordinates and excluded from point-based mapping and clustering.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
Convergence is recorded as evidentiary reinforcement (e.g., multi-source candidate status) rather than merged into a single record at the data-construction stage.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics", "table-Spatialization-logic-*"] -->
Raw location form | Precision class | Geocoded? | Geometry generated | Evidentiary status
---|---|---|---|---
Full street address | point | Yes | Yes (point) | Addressable
Street intersection | intersection | No | No | Valid non-point claim
Between X and Y | street_segment | No | No | Corridor reference
Neighborhood reference | neighborhood | No | Optional area | Approximate claim
Name-only reference | descriptive | No | No | Memory trace
Missing / unverifiable | unresolved | Attempted | No | Machine-limit evidence
<!-- #endregion -->

```python slideshow={"slide_type": ""} tags=["Code-Geocoding-pipeline-*", "hermeneutics"]
import re
from typing import Optional


# 1. Classify address type (not all locations are pointable)
def classify_location(raw_address: Optional[str]) -> str:
    """
    Distinguish between addressable and non-pointable spatial claims.
    """
    if raw_address is None:
        return "missing"

    s = raw_address.lower()

    if "between" in s:
        return "street_segment"
    if " and " in s or " & " in s:
        return "intersection"
    if re.match(r"^\d", s):
        return "street_address"

    return "descriptive"


# 2. Decide whether geocoding is appropriate
def should_geocode(location_type: str) -> bool:
    """
    Only stable street addresses are sent to geocoding.
    Other spatial claims remain valid but non-pointable.
    """
    return location_type == "street_address"


# 3. Record geocoding outcome without discarding failure
def record_geocode_result(match_status: str) -> str:
    """
    Geocoding failure is preserved as evidence,
    not silently corrected.
    """
    if match_status == "Match":
        return "point"
    else:
        return "unresolved"


# 4. Handle multi-source convergence
def record_convergence(source_count: int) -> str:
    """
    Convergence strengthens evidentiary status
    without merging records at construction stage.
    """
    if source_count > 1:
        return "multi_source_candidate"
    return "single_source"

```

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
### Making uncertainty auditable: evidence log and manual review
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
Because harmonization, temporal normalization, and spatialization are interpretive operations, the workflow makes uncertainty explicit rather than attempting to resolve it away. Each entry is accompanied by an evidence log that records provenance, temporal basis, spatial precision class, corroboration status, and the outcome of manual review. The evidence log functions not as passive metadata but as an active audit surface through which automated results, failure traces, and human decisions are made inspectable.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
Manual audit is an integral stage of the workflow. Audit decisions document whether a record is retained or excluded from the core dataset, the reasons for exclusion where applicable, and the basis on which spatial or temporal precision is assigned or withheld. Some entries are intentionally retained without spatial or temporal resolution, allowing historically meaningful mentions to remain visible without being coerced into cartographic form. Audit decisions are entered during review and stored in the evidence log; the scripts only scaffold the fields and validate consistency.
<!-- #endregion -->

```python slideshow={"slide_type": ""} tags=["data-table", "hermeneutics", "table-Evidence-log-schema-*"] jdh={"module": "object", "object": {"source": ["Evidence log schema"]}} 
# pandas package needs to be added to the requirements.txt 's file 
import pandas as pd
df = pd.read_excel("./data/Table 3. Evidence log schema.xlsx")
df
```

```python slideshow={"slide_type": ""} tags=["data-table", "hermeneutics", "table-Evidence-log-sample-rows-*"] jdh={"module": "object", "object": {"source": ["Evidence log sample rows"]}}
# pandas package needs to be added to the requirements.txt 's file 
import pandas as pd
df = pd.read_excel("./data/Table 4. Evidence log sample rows.xlsx")
df
```

```python tags=["figure-Spatial-Precision-Rubric-*", "hermeneutics"]
from IPython.display import Image, display
metadata = {
    "jdh": {
        "module": "object",
        "object": {
            "type": "image",
            "source": ["Spatial Precision Rubric"
                "Limit the image size to width 1000px"
            ]
        }
    }
}

display(Image("./data/Figure 1. Spatial-Precision Rubric.png", width=1000), metadata=metadata)

```

```python slideshow={"slide_type": ""} tags=["hermeneutics", "Code-Validation-checks-for-missingness-and-precision-flags-*"]
import json
import pandas as pd
import numpy as np


def _json_list(x):
    """Parse decades_norm stored as JSON list string; return [] if missing/unparseable."""
    if x is None or (isinstance(x, float) and np.isnan(x)) or str(x).strip() == "":
        return []
    try:
        v = json.loads(str(x))
        return v if isinstance(v, list) else []
    except Exception:
        return []


def derive_time_precision_class(df: pd.DataFrame) -> pd.Series:
    """
    decade      : decades_norm is a non-empty list
    year_range  : start_year or end_year exists but decades_norm empty
    missing     : no structured time signals
    """
    decades = df["decades_norm"].apply(_json_list)
    has_decade = decades.apply(lambda v: len(v) > 0)

    start = pd.to_numeric(df["start_year"], errors="coerce")
    end   = pd.to_numeric(df["end_year"], errors="coerce")
    has_year_bounds = start.notna() | end.notna()

    out = pd.Series(["missing"] * len(df), index=df.index)
    out.loc[has_decade] = "decade"
    out.loc[(~has_decade) & has_year_bounds] = "year_range"
    return out


def derive_spatial_precision_class(df: pd.DataFrame) -> pd.Series:
    """
    point          : lat/lon present
    intersection   : address_kind == 'intersection'
    non_pointable  : between_phrase / descriptive / multi_address
    missing        : none of the above
    """
    lat = pd.to_numeric(df["lat"], errors="coerce")
    lon = pd.to_numeric(df["lon"], errors="coerce")
    has_coords = lat.notna() & lon.notna()

    kind = df["address_kind"].fillna("missing").astype(str).str.lower()

    out = pd.Series(["missing"] * len(df), index=df.index)
    out.loc[kind.eq("intersection")] = "intersection"
    out.loc[kind.isin(["between_phrase", "descriptive", "multi_address"])] = "non_pointable"
    out.loc[(out.eq("missing")) & has_coords] = "point"
    return out


def validate_audit_trace(df: pd.DataFrame) -> pd.DataFrame:
    """
    Minimal JDH-style validation:
    - prevent over-pointification
    - require complete geocode trace when attempted
    """
    issues = []

    kind = df["address_kind"].fillna("missing").astype(str).str.lower()

    # (1) geocode_attempted implies geocode_status recorded (trace completeness)
    attempted = df["geocode_attempted"].fillna(False).astype(bool)
    status_missing = df["geocode_status"].isna() | (df["geocode_status"].astype(str).str.strip() == "")
    bad = attempted & status_missing
    for i in df.index[bad]:
        issues.append({"severity": "error", "entry_id": df.at[i, "entry_id"],
                       "issue": "geocode_attempted_without_status"})

    # (2) spatial_precision_class=point but address_kind non-pointable (over-pointification)
    non_pointable = kind.isin(["between_phrase", "descriptive", "multi_address"])
    bad = df["spatial_precision_class"].eq("point") & non_pointable
    for i in df.index[bad]:
        issues.append({"severity": "error", "entry_id": df.at[i, "entry_id"],
                       "issue": "over_pointification"})

    return pd.DataFrame(issues)
```

<!-- #region slideshow={"slide_type": ""} -->
### Interviews and cognitive mapping as a parallel evidentiary layer <a id="spatial-precision-logic"></a>
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
In addition to address-based records, the project incorporates a participant-generated evidentiary layer consisting of ten research sessions that paired semi-structured interviews with sketch-mapping activities. Sessions were conducted in English or Mandarin, recorded, transcribed, and anonymized using pseudonyms. Highly specific place references were generalized to neighborhood-scale descriptions where necessary to protect participants.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
Interview transcripts were segmented into discrete episodes and coded for recurring spatial practices and tactics, including access strategies, comfort calibration, risk management, and recognition cues. Cross-case comparison was conducted at the episode level to identify both recurring motifs and context-specific practices. Sketch maps were treated as image-based corroboration rather than coordinate evidence. Drawings were digitized and overlaid at a broad, non-precise scale to surface shared emphases and relational clusters. These materials are read in parallel with the address-based corpus, providing a second register of evidence that foregrounds lived spatial knowledge, memory, and tactic, without requiring that such knowledge be stabilized as an addressable site.
<!-- #endregion -->

```python tags=["figure-Overlay-montage-of-sketch-map-layers-*"]
from IPython.display import Image, display
metadata = {
    "jdh": {
        "module": "object",
        "object": {
            "type": "image",
            "source": ["Overlay montage of sketch-map layers"
                "Limit the image size to width 1000px"
            ]
        }
    }
}

display(Image("./data/Figure 2. Overlay montage of sketch-map layers.png", width=1000), metadata=metadata)

```

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
These interview and drawing materials were generated as part of a graduate-level course project completed prior to manuscript preparation. The present article is based on secondary analysis of these materials, and no new participant recruitment or data collection was conducted for this publication. Participants were informed of the project’s purpose and the voluntary nature of participation, and agreed to recording and use of de-identified excerpts. To reduce identification and spatial risks, place references are generalized and sketch maps are treated as interpretive traces rather than locational claims. Original recordings and full transcripts are not publicly released.
<!-- #endregion -->

```python slideshow={"slide_type": ""} tags=["data-table", "hermeneutics", "table-Episode-level-codebook-*"] jdh={"module": "object", "object": {"source": ["Sample coded transcript excerpt"]}}
# pandas package needs to be added to the requirements.txt 's file 
import pandas as pd
df = pd.read_excel("./data/Table 5. Episode-level Codebook (Interviews + Sketch Maps).xlsx")
df
```

```python tags=["hermeneutics", "figure-sample-coded-transcript-excerpt-*"]
from IPython.display import Image, display
metadata = {
    "jdh": {
        "module": "object",
        "object": {
            "type": "image",
            "source": ["Sample coded transcript excerpt"
                "Limit the image size to width 1000px"
            ]
        }
    }
}

display(Image("./data/Figure 3. Sample coded transcript excerpt.png", width=1000), metadata=metadata)

```

<!-- #region slideshow={"slide_type": ""} -->
## Findings
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
### What the maps show: cross-source patterns and source effects
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
The address-based layer organized by decade shows where queer and sapphic traces become mappable as sites, and how those traces thicken or thin depending on which sources are present. This decade-based view reads less as a single stable geography than as a shifting evidentiary surface, whose density changes with the availability of listings, commemorative entries, community memory records, and bar-centered reconstructions.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
Across the side-by-side views, different sources consistently light up different kinds of places. The NYC LGBT Historic Sites Project tends to foreground verifiable, publicly narratable sites, often yielding a cleaner set of entries that read as durable venues, organizations, and commemorated events. The Addresses Project broadens what appears by mapping memory-based and community-transmitted place knowledge, including episodic formations that are less likely to enter institutional inventories. Stegall’s thesis contributes a bar-centered reconstruction that can thicken nightlife history, while also requiring additional spatialization work in this project because coordinates were not consistently provided. Stable clusters such as Womanbooks reflect repeated documentation across sources rather than multiple spatial instances.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
A concrete example is Manhattan North. Across the decade-sliced maps, Manhattan North appears as a strong cluster in the 1930s and 1940s, while remaining faint in the 1920s and nearly absent in the 1950s. This pattern is better read as a visibility window than as evidence of a stable or discontinuous geography of queer life: a period when particular documentary regimes enter the workflow and make address-level presence operable. In the compiled corpus, this Manhattan North “surge” becomes legible largely because the evidentiary field includes Map of Harlem Night Spots Frequented by African American Lesbians in the 1930s and 1940s from The Other Black Woman (Gray 1983, as cited in Stegall 2019), alongside bar-centered reconstructions that thicken nightlife history. The cluster thus demonstrates how “presence” can appear on an address-based timeline when a specific document becomes usable within the project’s schema, rather than serving as a direct proxy for the emergence or disappearance of social practice.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
Read across the corpus, clustering is best interpreted as the intersection of urban social concentration and documentary concentration. In this sense, the maps are used to compare evidence conditions as much as to infer spatial concentration.
<!-- #endregion -->

```python tags=["figure-dacade-timeline-view-of-the-compiled-corpus-*"]
from IPython.display import Image, display
metadata = {
    "jdh": {
        "module": "object",
        "object": {
            "type": "image",
            "source": [
                "Limit the image size to width 1000px"
            ]
        }
    }
}

display(Image("./data/Figure 4. Decade timeline view of the compiled corpus.png", width=1000), metadata=metadata)

```

```python tags=["figure-dacade-timeline-view-of-the-compiled-corpus-*"]
from IPython.display import Image, display
metadata = {
    "jdh": {
        "module": "object",
        "object": {
            "type": "image",
            "source": [
                "Limit the image size to width 1000px"
            ]
        }
    }
}

display(Image("./data/Figure 5. Cross-source overlap of address-based entries by decade.png", width=1000), metadata=metadata)

```

```python tags=["figure-1930s-to-1940s-Manhattan-North-cluster-evidence-mechanism-highlight-*"]
from IPython.display import Image, display
metadata = {
    "jdh": {
        "module": "object",
        "object": {
            "type": "image",
            "source": [
                "Limit the image size to width 1000px"
            ]
        }
    }
}

display(Image("./data/Figure 6. 1930s-1940s Manhattan North cluster evidence mechanism highlight.png", width=1000), metadata=metadata)

```

<!-- #region slideshow={"slide_type": ""} -->
### What the maps do not show: limits of address-based legibility
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
Even after integration, the corpus remains constrained by addressable sites, and practices organized through pop-ups, semi-private hosting circuits, selective disclosure, or event-based movement often remain thin or absent in the mapped view. Mattson identifies one mechanism that helps explain this thinness in address-based bar records: national guides tracking queer spaces were produced by all-male teams until the early 1990s, and a women’s guide did not appear until 1990.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
A concrete illustration of this constraint is provided by one midtown nightlife venue that appears across the corpus under incompatible framings. In a scholarly reconstruction (S3), the venue is registered through women-only programming on specific nights in the early 1990s, making it legible as lesbian-coded under a programmatic logic. In a community directory record (S2), the same vicinity is framed differently (as a drag-oriented venue on Eleventh Avenue in the mid-40s), while later public accounts of the site are structured primarily through enforcement narratives rather than community description. Read together, these traces suggest that a space may become “sapphic” in historically bounded ways (e.g., by weekday, by event, by entry rule) without stabilizing as a single, continuously nameable “lesbian bar” in address-based records.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
This divergence is treated here as an evidentiary condition rather than a discrepancy to be resolved. It illustrates why the workflow does not force cross-source convergence into a single venue category: multi-phase lineages and program-specific identities are preserved through provenance and corroboration fields so that classification instability remains visible in interpretation.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
A second constraint concerns spatial precision. A substantial portion of historical traces enters the corpus in forms such as intersections, street segments (“between” descriptions), or name-only references; these are treated as legitimate spatial claims rather than errors, and their persistence helps explain why the evidence log contains stable non-point geometries alongside point locations.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
Taken together, these constraints show that “not listed” can reflect the limits of what was recorded and circulated, not a direct proxy for nonexistence. They also explain why some entries are represented only at neighborhood or corridor scale. The workflow keeps these limits explicit through spatial-precision flags and the evidence log.
<!-- #endregion -->

```python tags=["figure-Mapped-spatial-precision-by-decade-*"]
from IPython.display import Image, display
metadata = {
    "jdh": {
        "module": "object",
        "object": {
            "type": "image",
            "source": [
                "Limit the image size to width 1000px"
            ]
        }
    }
}

display(Image("./data/Figure 7. Mapped spatial precision by decade.png", width=1000), metadata=metadata)

```

```python tags=["figure-Unmapped-entries-by-decade-*"]
from IPython.display import Image, display
metadata = {
    "jdh": {
        "module": "object",
        "object": {
            "type": "image",
            "source": [
                "Limit the image size to width 1000px"
            ]
        }
    }
}

display(Image("./data/Figure 8. Unmapped entries by decade (split by source).png", width=1000), metadata=metadata)

```

<!-- #region slideshow={"slide_type": ""} -->
### What interviews and cognitive mapping add: perspective, tactics, and atmosphere
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
Interviews also surface constraints that maps cannot encode as spatial coordinates, including affordability, social dynamics, and embodied risk management. One participant described how income volatility shapes what feels accessible and which venues become viable. Another emphasized the role of semi-private gatherings as dependable infrastructures of safety and comfort. These accounts describe conditions and tactics of use, but not in a form that reliably stabilizes as addressable records.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
Cognitive maps contribute as image-based traces of memory and perception rather than georeferenced data. Analytically, they are read for emphasis, clustering, and narrated linkage: what participants choose to draw, what they connect, and what they leave blank. Overlays are treated as broad-scale corroboration, allowing recurring centers and habitual pathways to be seen without converting drawings into coordinate-precise claims.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
Read alongside the compiled corpus, the participant layer clarifies the stakes of legibility by distinguishing “not present in the record” from “present in practice but structurally hard to stabilize.” It further shows how atmosphere and tacit recognition shape whether a space is experienced as usable or avoidable, including the comfort produced by intentionally sapphic settings where shared expectations can remain unspoken.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
## Discussion and Conclusion
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
### Discussion: beyond “abcense”
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
The layered method developed here treats countability as a historical outcome rather than a neutral metric. It depends on whether a place could be named, repeatedly documented, and retained as an address-based trace. This reframing matters because “abcense” narratives often compress two different processes into one curve: shifts in social life and shifts in recordability. In a field assembled from heterogeneous documentary regimes, thinning on a map can register changes in verification norms, category availability, and survivable forms of publicity as much as changes in where and how people gathered. Absence is therefore read not as a residual technical problem but as a historical signal about documentary conditions and the politics of legibility.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
Methodologically, the project advances a spatial form of source criticism. Integration is not used to synthesize a neutral baseline. It is used to keep sources comparable while preserving their differences, so that overlap and non-overlap become interpretable features of evidence production. In this frame, a cluster is not only a spatial concentration but also a documentary event, and a silence is not only a gap but a prompt to ask what forms of queer presence were least likely to survive as repeatable records.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
The constellation framing names the kind of historical object that becomes visible under this approach. It describes a field where sapphic histories are carried through partial traces that do not reliably converge into one stable geography, and where nonalignment across records is itself informative. Constellations are not proposed as a counter-map that completes the archive. They are a way to hold together fragmented traces, relational pathways, and episodic gatherings without forcing them into a single evidentiary standard.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
Finally, the project suggests a transferable strategy for other histories marked by uneven documentation. Constellation-based work is most useful where archives are fragmented, where naming can carry risk, and where social worlds rely on informal infrastructures that do not consistently stabilize as addressable sites. In such cases, the aim is not to replace missing records with speculative precision, but to build a comparative evidentiary frame that can track how legibility is produced, where uncertainty must remain, and how different kinds of traces can be read together without being collapsed into the same kind of data.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
### Limits and scope conditions
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
The project’s comparability is bounded by the sources it can ethically and practically assemble. Even with harmonization, the corpus inherits uneven coverage across neighborhoods, decades, and sub-scenes, and it remains sensitive to survivorship in records and to the safety constraints that shape what can be named. Geocoding and temporal placement introduce interpretive judgment, especially when addresses are partial, historical, or intentionally vague; the evidence log is meant to keep those judgments visible rather than to remove them.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} tags=["hermeneutics"] -->
Participant materials are likewise bounded. Ten sessions cannot represent the full diversity of sapphic New York, and the choice to generalize place references protects participants at the cost of spatial specificity. Cognitive maps are not geospatial measurements; they are image-based artifacts of memory and perception, useful for interpretation and corroboration but not for coordinate-precise inference.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
### Conclusion: absence as an object of inquiry
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
The project began from a recurrent tension between what contemporary inventories make easy to count and what queer sapphic life has often made difficult to record. Read across decades, the compiled corpus shows that density and scarcity are frequently properties of documentation, including where venues can be listed, where categories fit, and where naming is sustainable over time. The map thus supports a comparative reading of legibility conditions rather than a definitive measure of queer sapphic social presence.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
Across sources, the analysis indicates that disappearance cannot be interpreted through mapped counts alone. What is most visible tends to be what is durable enough to be listed, verifiable enough to be narrated, and aligned enough with existing classificatory systems to recur in public records. This shifts the historical question from whether sapphic space existed to how particular documentary forms and institutional horizons made certain forms of existence easier to register than others. It also suggests that integration is best understood as source criticism, because bringing records into one frame makes divergences historically interpretable rather than merely inconsistent.
<!-- #endregion -->

<!-- #region slideshow={"slide_type": ""} -->
Participant materials extend this evidentiary argument without being reduced to geocoded points. Interviews and sketch maps provide a reflective counter-layer that clarifies what address-based traces cannot stabilize, including how access is negotiated through cost, disclosure, and social atmosphere, and how spatial practice may persist through episodic gatherings and relational pathways. In this layered evidentiary field, absence is not only a limit of the archive but a historical object that illuminates changing conditions of queer legibility and the practical work of sustaining community. Future work could apply the same source-aware timeline approach to other cities or other under-recorded formations, using the evidence log not only as documentation but as a comparative instrument for tracing how legibility regimes shift across contexts.
<!-- #endregion -->
