# Module-6-Doing-math-in-R-part-2
# Define the matrices A and B
A <- matrix(c(2, 0, 1, 3), ncol=2)
B <- matrix(c(5, 2, 4, -1), ncol=2)

# Perform matrix addition and subtraction
AplusB <- A + B
AminusB <- A - B

# Print results
AplusB
AminusB

diagonal_matrix <- diag(c(4, 1, 2, 3))
diagonal_matrix

# Create the base diagonal matrix
diagonal_matrix <- diag(3, 5)  # Create a 5x5 diagonal matrix with 3 on the diagonal


diagonal_matrix[1, ] <- c(3, 1, 1, 1, 1)

diagonal_matrix[2, 1] <- 2
diagonal_matrix[3, 1] <- 2
diagonal_matrix[4, 1] <- 2
diagonal_matrix[5, 1] <- 2
diagonal_matrix
