# Binance Captcha Solver

<div>
    <img src="https://wakatime.com/badge/user/839267df-3912-44c6-97f4-9e3f0425b716/project/06032300-f18e-4196-bb00-404af191bdce.svg" alt="wakatime">
</div>

---

## Example Usage

```python
from binance.session import BinanceCaptcha

binance = BinanceCaptcha(
    biz_id="login",
    security_check_response_validate_id="7d1bf5349be4481c8b2de29cc24f8451"
)

token = binance.solve()

print(token)
# token = captcha#e479223...416da2622fe0-pvazmct322p...NwVAngrDSLmfy
```

---


## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---
