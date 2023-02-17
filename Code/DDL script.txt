/******Object:  Table [dbo].[AthletesOlympics]    ******/
SET ANSI_NULLS ON
GO
SET QUOTED_IDENTIFIER ON
GO
CREATE TABLE [dbo].[AthletesOlympics](
    [PersonName] [nvarchar](100) NULL,
    [Country] [nvarchar](100) NULL,
    [Discipline] [nvarchar](100) NULL
    )
GO


/****** Object:  Table [dbo].[CoachesOlympics]   ******/
SET ANSI_NULLS ON
GO
SET QUOTED_IDENTIFIER ON
GO
CREATE TABLE [dbo].[CoachesOlympics](
    [CoachName] [nvarchar](100) NULL,
    [Country] [nvarchar](100) NULL,
    [Discipline] [nvarchar](100) NULL,
    [Event] [nvarchar](50) NULL
    )
GO

/****** Object:  Table [dbo].[AthletesGenderOlympics]   ******/
SET ANSI_NULLS ON
GO
SET QUOTED_IDENTIFIER ON
GO
CREATE TABLE [dbo].[AthletesGenderOlympics](
    [Discipline] [nvarchar](100) NULL,
    [Male] [int] NULL,
    [Female] [int] NULL,
    [TotalAthletes] [int] NULL
    )
GO

/****** Object:  Table [dbo].[CountryMedalsOlympics]   ******/
SET ANSI_NULLS ON
GO
SET QUOTED_IDENTIFIER ON
GO
CREATE TABLE [dbo].[CountryMedalsOlympics](
    [RankId] [int] NULL,
    [Country] [nvarchar](100) NULL,
    [Gold] [int] NULL,
    [Silver] [int] NULL,
    [Bronze] [int] NULL,
    [Total] [int] NULL,
    [RankByTotal] [int] NULL
    ) 
GO

/****** Object:  Table [dbo].[TeamOlympics]   ******/
SET ANSI_NULLS ON
GO
SET QUOTED_IDENTIFIER ON
GO
CREATE TABLE [dbo].[TeamOlympics](
    [TeamName] [nvarchar](100) NULL,
    [Country] [nvarchar](100) NULL,
    [Discipline] [nvarchar](100) NULL,
    [Event] [nvarchar](50) NULL
    )
GO
