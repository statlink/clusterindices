\name{clust.plot}
\alias{clust.plot}
\title{
Visualization of the \eqn{K}--means algorithm results
}

\description{
Visualization of the \eqn{K}--means algorithm results.
}

\usage{
clust.plot(mod, x)
}

\arguments{
\item{mod}{
The output of the kmeans() function.
}
\item{x}{
A matrix with the data.
}
}

\details{
The function performs PCA and plots the data onto the first two dimensions, constructs the convex hull of the groups and plots them with different colours.
}

\value{
A plot.
}

\references{
Tsagris M. and Kontemeniotis N. (2025). Simplicial clustering using the \eqn{\alpha}--transformation.
Lobachevskii Journal of Mathematics, 46: 6471–-6482.
https://arxiv.org/pdf/2509.05945.

Garcia-Escudero Luis A., Gordaliza Alfonso, Matran Carlos, Mayo-Iscar Agustin. (2008). A general
trimming approach to robust cluster analysis. Annals of Statistics 36(3): 1324--1345.
}

\author{
Michail Tsagris and Nikolaos Kontemeniotis.

R implementation and documentation: Michail Tsagris \email{mtsagris@uoc.gr} and
Nikolaos Kontemeniotis \email{kontemeniotisn@gmail.com}.
}

%\note{
%%  ~~further notes~~
%}

\seealso{
\code{\link{cikmeans}
}
}

\examples{
y <- as.matrix(iris[, 1:4])
mod <- cikmeans( y, ncl = 3, a = 1 )
clust.plot(mod[[ 1 ]], z )
}

