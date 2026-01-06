
import re

def normalize_company_name(company_name):
    """
    Normalize CAF SofSol company name to a standard format.
    
    Args:
        company_name (str | None): Raw company name from Excel
    
    Returns:
        str | None: Normalized company name or None if input is invalid
    """
    if not company_name or not isinstance(company_name, str):
        return None

    # Remove extra spaces, tabs, and normalize case
    cleaned = re.
