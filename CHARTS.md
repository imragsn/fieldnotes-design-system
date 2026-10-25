# Fieldnotes — Chart guide 1.2.0

| ID | Rule |
| --- | --- |
| CH01 / Question | Comparison→bars/dots; trend→line; part-to-whole→100%stackedbar; distribution→histogram/dots; relationship→scatter; uncertainty→intervals; exact lookup→table. |
| CH02 / Bar | Horizontal preferred for long labels;<=8 categories on main slide.Sort by value unless ordinal/time order.Zero baseline required.Negative values around visiblezero.Square bar ends, even in rounded cards. |
| CH03 / Grouped comparison | 2-3 series per category,<=6categories; equal scales and consistent order.Use dotplot when groups become crowded.No dualaxes by default. |
| CH04 / Time series | Up to4series; true time spacing.Label nonzero domain if justified; missing actual points break line.Actual solid, target dashed, forecast dashed+boundary+label. |
| CH05 / Whole | Exclusive exhaustive categories, denominator explicit;<=5segments.Fixed order, totals reconcile; use a table if parts do not form a whole.Donut optional only2-5positive parts; bars preferred for precision. |
| CH06 / Distribution | Raw observations or documented bins.Label boundaries, count/sample size; include zero bins; compare with identical bins.No arbitrary smoothing/outlier deletion. |
| CH07 / Scatter | Paired observations with units, scope and n.Correlation is not cause.Fit only if justified with stated method; never fabricate a regression. |
| CH08 / Actual-target | Actual, target, period and benchmark definition.Bullet chart/dots preferred.Written threshold required for qualitative bands.Unknown status=Not assessed. |
| CH09 / Waterfall | Opening+signed additive changes=closing.Totals startzero; changes float from cumulative balance.Show connectors and signed labels; separate total/delta encoding. |
| CH10 / Heatmap | Sequential scale for magnitude; diverging only with meaningful midpoint.Values/legend required.Missing uses hatch+N/A, neverzero.Contrast label against each cell fill. |
| CH11 / Interval | Show supplied lower/upper/central value and range/confidence definition.No invented intervals; prediction and confidence intervals are different. |
| CH12 / Map | Only if geography matters.Rates for choropleth; rawcounts may need proportional symbols.Source coordinates/basemap licence, class bins, denominator, cutoff.Informational network differs from decoration. |
| CH13 / Canvas | Units at1600x900.Read chart labels>=22px; Present >=28px.Legend/directlabels same minimum.Full plot should occupy>=55%of content width; split instead of shrink. |
| CH14 / Marks | Use3px line and10px marker atnative canvas;2px zeroaxis/outline,1px decorativegrid.4-6major ticks using1/2/2.5/5x10^n.Never use rounded bars,3D, area/volume pictograms or shadow as quantitative encoding. |
| CH15 / Color | Fixed series mapping:#202622, #285B86, #276347, #A52F3B.Primaryfocus#F58A49on#FAF9F6requires2px#202622outline.No pale accent alone for meaningful marks.Status colors require state and threshold; do not assign palette decoration a status meaning. |
| CH16 / Typography | Direct labels preferred; avoid overlapping endpoints, slanted ticks and detached units.Resolve collision by widening, shortening truthful labels, or splitting.Critical caveats use body size, not footer. |
| CH17 / Numbers | Source, period, scope, units, denominator andcutoff explicit.40%→50%=+10percentage points or+25%relative; specifywhich.Compute raw, round display only. |
| CH18 / Missing | 0, null, N/A andNotassessed differ.No null-to-zero conversion; no silent interpolation.Show gaps, excluded sample and noncomparable periods. |
| CH19 / Semantics | Colors/labels consistent across deck.Pale focus outlined; series distinguished by marker/dash/directlabel, not hue alone.No default causal headline from association. |
| CH20 / Access and export | Provide concise accessible summary and underlying data table; SVGtitle/desc; editable native chart+source data if supported.SVGspecimen is not native chart master.Check actual render, textselection and readingorder where supported. |
| CH21 / Integrity gate | Recompute totals, deltas, percentages, denominators, rounding and intervals.Check domain/baseline, signs, nulls, seriesmapping, labelcollisions, source and final export. |
| CH22 / Trace record | chartID, question, type, datasetID, source locator, period/cutoff, units, denominator, fieldtypes, transformation, domain, ticks, mapping, focusreason, caveat, summary, QAresult. |

## Original detailed contracts

See the preserved data-integrity section in DESIGN-SYSTEM.md.
