# Public Market Comparison Methodologies

## Overview

Comparing private equity and venture capital performance to public markets is methodologically complex due to fundamental differences in cash flow timing, liquidity, and risk characteristics. This document reviews key approaches and findings.

## Core Methodological Challenges

### 1. Cash Flow Timing Differences
- **VC/PE**: Irregular cash flows over 7-10 year periods with J-curve effects
- **Public Markets**: Continuous pricing and immediate liquidity
- **Challenge**: Comparing IRR (money-weighted) vs. TWR (time-weighted) returns

### 2. Risk and Liquidity Differences
- **VC/PE**: Illiquid, high systematic risk, extreme return dispersion
- **Public Markets**: Liquid, measurable systematic risk, normal distribution
- **Challenge**: Proper risk adjustment for illiquidity and systematic risk

### 3. Benchmark Selection
- **Broad Market**: S&P 500, Russell 3000
- **Size-Focused**: Russell 2000, S&P SmallCap 600
- **Sector-Focused**: NASDAQ, sector-specific indices
- **Style-Focused**: Growth, value, high-beta indices

## Public Market Equivalent (PME) Methods

### 1. Kaplan-Schoar PME (2005)
**Method**: 
- Invest VC cash calls in public market index
- Distribute VC distributions from accumulated public market value
- PME = Final VC value / Final public market value

**Advantages**:
- Simple, intuitive methodology
- Direct comparison of final values

**Limitations**:
- Doesn't properly handle negative index returns
- Can be manipulated through timing
- Ignores risk differences

### 2. Long-Nickels PME (2007)
**Method**:
- Modified KS-PME that handles negative index returns
- Uses absolute values to prevent mathematical issues
- Provides more stable results

**Advantages**:
- Addresses KS-PME technical issues
- More robust across different market conditions

**Limitations**:
- Still doesn't address fundamental risk differences
- Limited theoretical foundation

### 3. Direct Alpha PME (Gredil et al.)
**Method**:
- Calculates excess return over public market directly
- Uses regression-based approach to estimate alpha
- Provides confidence intervals for outperformance

**Advantages**:
- Statistically rigorous approach
- Provides uncertainty measures
- Handles various benchmark specifications

**Limitations**:
- More complex to implement
- Requires statistical expertise

### 4. mPME (Modified PME) - Cambridge Associates
**Method**:
- Adjusts PME calculation for fund size and style
- Uses multiple benchmarks based on fund characteristics
- Incorporates risk factor adjustments

**Advantages**:
- More nuanced benchmark selection
- Accounts for fund-specific characteristics

**Limitations**:
- Requires detailed fund information
- Methodology not fully disclosed

## Risk-Adjustment Methods

### 1. CAPM-Based Adjustments
**Approach**: Adjust public market returns for beta differences
**Findings**: VC beta typically 1.3-2.0 vs. public markets
**Limitations**: CAPM may not capture VC risk characteristics

### 2. Fama-French Three-Factor
**Approach**: Adjust for size, value, and market risk factors
**Findings**: VC has significant small-cap and growth exposure
**Limitations**: Factors based on public market relationships

### 3. Stochastic Discount Factor (SDF)
**Approach**: More general risk adjustment using SDF framework
**Findings**: Allows flexible risk specifications for VC
**Advantages**: Theoretically sound, handles irregular cash flows

## Key Empirical Findings

### 1. Aggregate Performance Comparisons

**Harris, Jenkinson & Kaplan (2020)**:
- VC net returns approximately match S&P 500 (median PME ~1.0)
- Top quartile VC significantly outperforms (PME 1.4-1.6)
- Strong performance dispersion (bottom quartile PME 0.6-0.8)

**Ouyang, Yu & Jagannathan (2020)**:
- Aggregate VC portfolio IRR: 22% (1980-2006 vintages)
- PME of 1.44 vs. public markets
- Performance driven by top 5% of investments

**JP Morgan "Food Fight" Analysis (2021)**:
- VC 20-year IRR: 13.7% vs. public markets 10.5%
- But gap narrowing in recent vintages
- Higher dispersion in VC creates selection challenge

### 2. Risk-Adjusted Performance

**Korteweg & Nagel (2013)**:
- VC fund abnormal returns close to zero after fees
- VC company investments earn positive abnormal returns
- Risk adjustment crucial for proper evaluation

**Cochrane (2005)**:
- VC systematic risk much higher than public markets
- Risk-adjusted returns closer to market returns
- Extreme positive skewness important factor

### 3. Vintage Year Effects on Comparisons

**StepStone "Vintage Year Power Law" (2023)**:
- Post-recession vintages outperform by 300-500 bps
- Peak market vintages underperform by 200-400 bps
- Vintage diversification reduces public market comparison volatility

## Recent Developments and Debates

### 1. "Private Market Premium" Debate
**Proponents**: Private markets offer liquidity premium and skill-based alpha
**Skeptics**: Returns explained by beta exposure and selection bias
**Evidence**: Mixed, depends on methodology and time period

### 2. Factor Replication Studies
**MSCI Approach**: Replicate PE characteristics in public markets
- Explains ~200 bps of 450 bps outperformance through factors
- Remaining 250 bps from leverage, valuation smoothing, alpha

**BlackRock Analysis**: Similar factor-based replication
- Public market factor portfolios can replicate much PE performance
- Questions about fees and liquidity costs

### 3. Benchmarking Evolution
**Traditional**: Single index (S&P 500) comparison
**Modern**: Multi-factor, risk-adjusted, style-specific benchmarks
**Future**: AI-driven, dynamic benchmarking approaches

## Practical Implementation Guidelines

### For Limited Partners
1. **Use Multiple Methods**: Don't rely on single PME calculation
2. **Consider Risk Adjustment**: Account for systematic risk differences
3. **Benchmark Selection**: Match benchmark to fund strategy
4. **Vintage Cohort Analysis**: Compare within vintage years
5. **Long-term Perspective**: Evaluate over full fund lifecycle

### For General Partners
1. **Transparent Reporting**: Provide multiple performance metrics
2. **Benchmark Disclosure**: Explain benchmark selection rationale
3. **Risk Communication**: Clearly communicate risk profile
4. **Vintage Context**: Position performance within vintage cohort

### For Researchers
1. **Data Quality**: Use institutional-quality, unbiased datasets
2. **Methodology Transparency**: Fully disclose methodological choices
3. **Robustness Testing**: Test across multiple specifications
4. **Economic Significance**: Focus on economically meaningful differences

## Future Research Directions

1. **Alternative Benchmarks**: Beyond traditional equity indices
2. **International Comparisons**: Non-U.S. market dynamics
3. **ESG Integration**: How ESG factors affect comparisons
4. **Technology Impact**: Digital transformation effects on benchmarking
5. **Real-time Valuation**: Move toward more frequent valuation updates