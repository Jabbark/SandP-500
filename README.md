# SandP-500

1)
-- Which compnies are currently the TOP 10 by market capitlization in the S and P 500
SELECT Symbol, Name, `Market Cap`
FROM finance.financials
ORDER BY `Market Cap`DESC
Limit 10
